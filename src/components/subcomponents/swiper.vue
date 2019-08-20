<template>
    <div>
        <!--轮播图区域-->
        <mt-swipe :auto="4000">
            <mt-swipe-item>1</mt-swipe-item>
            <mt-swipe-item>2</mt-swipe-item>
            <mt-swipe-item>3</mt-swipe-item>
            <!--         在组件中，使用v-for循环的话，一定要使用 key -->
<!--            <mt-swipe-item v-for="item in lunbotuList" :key="item.url">-->
<!--                <img :src="item.img" alt="" :class="{full: isfull}">-->
<!--            </mt-swipe-item>-->
        </mt-swipe>
    </div>
</template>

<script>
  export default {
    props: ["lunbotuList"]
    // props: ["lunbotuList", "isfull"]
  }
</script>

<style lang="scss" scoped>
    .mint-swipe {
        height: 200px;

        .mint-swipe-item {
            text-align: center;
            &:nth-child(1) {
                background-color: #1b6d85;
            }

            &:nth-child(2) {
                background-color: #dd524d;
            }

            &:nth-child(3) {
                background-color: #398439;
            }

            img {
                height: 100%;
                /*width: 100%;*/
            }
        }
    }

    .full {
        width: 100%;
    }
</style>