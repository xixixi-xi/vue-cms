<template>
    <div>
        <ul class="mui-table-view">
            <li class="mui-table-view-cell mui-media">
                <router-link to="/home/newsinfo">
                    <img class="mui-media-object mui-pull-left" src="../../images/shuijiao.jpg">
                    <div class="mui-media-body">
                        幸福
                        <p class='mui-ellipsis'>
                            <span>发表时间：2012-12-12 12:12:12</span>
                            <span>点击：0次</span>
                        </p>
                    </div>
                </router-link>
            </li>
            <li class="mui-table-view-cell mui-media">
                <router-link to="/home/newsinfo">
                    <img class="mui-media-object mui-pull-left" src="../../images/shuijiao.jpg">
                    <div class="mui-media-body">
                        幸福
                        <p class='mui-ellipsis'>
                            <span>发表时间：2012-12-12 12:12:12</span>
                            <span>点击：0次</span>
                        </p>
                    </div>
                </router-link>
            </li>
            <li class="mui-table-view-cell mui-media">
                <router-link to="/home/newsinfo">
                    <img class="mui-media-object mui-pull-left" src="../../images/shuijiao.jpg">
                    <div class="mui-media-body">
                        幸福
                        <p class='mui-ellipsis'>
                            <span>发表时间：2012-12-12 12:12:12</span>
                            <span>点击：0次</span>
                        </p>
                    </div>
                </router-link>
            </li>
            <li class="mui-table-view-cell mui-media">
                <router-link to="/home/newsinfo">
                    <img class="mui-media-object mui-pull-left" src="../../images/shuijiao.jpg">
                    <div class="mui-media-body">
                        幸福
                        <p class='mui-ellipsis'>
                            <span>发表时间：2012-12-12 12:12:12</span>
                            <span>点击：0次</span>
                        </p>
                    </div>
                </router-link>
            </li>
            <li class="mui-table-view-cell mui-media">
                <router-link to="/home/newsinfo">
                    <img class="mui-media-object mui-pull-left" src="../../images/shuijiao.jpg">
                    <div class="mui-media-body">
                        幸福
                        <p class='mui-ellipsis'>
                            <span>发表时间：2012-12-12 12:12:12</span>
                            <span>点击：0次</span>
                        </p>
                    </div>
                </router-link>
            </li>
            <li class="mui-table-view-cell mui-media">
                <router-link to="/home/newsinfo">
                    <img class="mui-media-object mui-pull-left" src="../../images/shuijiao.jpg">
                    <div class="mui-media-body">
                        幸福
                        <p class='mui-ellipsis'>
                            <span>发表时间：2012-12-12 12:12:12</span>
                            <span>点击：0次</span>
                        </p>
                    </div>
                </router-link>
            </li>
            <li class="mui-table-view-cell mui-media">
                <router-link to="/home/newsinfo">
                    <img class="mui-media-object mui-pull-left" src="../../images/shuijiao.jpg">
                    <div class="mui-media-body">
                        幸福
                        <p class='mui-ellipsis'>
                            <span>发表时间：2012-12-12 12:12:12</span>
                            <span>点击：0次</span>
                        </p>
                    </div>
                </router-link>
            </li>
            <li class="mui-table-view-cell mui-media">
                <router-link to="/home/newsinfo">
                    <img class="mui-media-object mui-pull-left" src="../../images/shuijiao.jpg">
                    <div class="mui-media-body">
                        幸福
                        <p class='mui-ellipsis'>
                            <span>发表时间：2012-12-12 12:12:12</span>
                            <span>点击：0次</span>
                        </p>
                    </div>
                </router-link>
            </li>
            <li class="mui-table-view-cell mui-media">
                <router-link to="/home/newsinfo">
                    <img class="mui-media-object mui-pull-left" src="../../images/shuijiao.jpg">
                    <div class="mui-media-body">
                        幸福
                        <p class='mui-ellipsis'>
                            <span>发表时间：2012-12-12 12:12:12</span>
                            <span>点击：0次</span>
                        </p>
                    </div>
                </router-link>
            </li>
            <li class="mui-table-view-cell mui-media">
                <router-link to="/home/newsinfo">
                    <img class="mui-media-object mui-pull-left" src="../../images/shuijiao.jpg">
                    <div class="mui-media-body">
                        幸福
                        <p class='mui-ellipsis'>
                            <span>发表时间：2012-12-12 12:12:12</span>
                            <span>点击：0次</span>
                        </p>
                    </div>
                </router-link>
            </li>
            <li class="mui-table-view-cell mui-media">
                <router-link to="/home/newsinfo">
                    <img class="mui-media-object mui-pull-left" src="../../images/shuijiao.jpg">
                    <div class="mui-media-body">
                        幸福
                        <p class='mui-ellipsis'>
                            <span>发表时间：2012-12-12 12:12:12</span>
                            <span>点击：0次</span>
                        </p>
                    </div>
                </router-link>
            </li>
        </ul>

<!--        vue-resoure获取数据-->
<!--        <ul class="mui-table-view">-->
<!--            <li class="mui-table-view-cell mui-media" v-for="item in newslist" :key="item.id">-->
<!--                <router-link :to="'/home/newsinfo/' + item.id">-->
<!--                    <img class="mui-media-object mui-pull-left" :src="item.img_url">-->
<!--                    <div class="mui-media-body">-->
<!--                        <h1>{{ item.title }}</h1>-->
<!--                        <p class='mui-ellipsis'>-->
<!--                            <span>发表时间：{{ item.add_time | dateFormat }}</span>-->
<!--                            <span>点击：{{item.click}}次</span>-->
<!--                        </p>-->
<!--                    </div>-->
<!--                </router-link>-->
<!--            </li>-->

<!--        </ul>-->


    </div>
</template>

<script>
  import { Toast } from "mint-ui";

  export default {
    data() {
      return {
        newslist: [] // 新闻列表
      };
    },
    created() {
      //this.getNewsList();
    },
    // methods: {
    //   getNewsList() {
    //     // 获取新闻列表
    //     this.$http.get("api/getnewslist").then(result => {
    //       if (result.body.status === 0) {
    //         // 如果没有失败，应该把数据保存到 data 上
    //         this.newslist = result.body.message;
    //       } else {
    //         Toast("获取新闻列表失败！");
    //       }
    //     });
    //   }
    // }
  };
</script>

<style lang="scss" scoped>
.mui-table-view {
    li {
        font-size: 14px;
        .mui-ellipsis {
            font-size: 12px;
            color: #2e6da4;
            display: flex;
            justify-content: space-between;
        }
    }
}
</style>