<template>
    <div class="goodsdesc-container">
        <h3>小米(Mi)小米Note 16G双网通版</h3>
        <hr>
        <div class="content">
            电池信息
            电池是否可拆卸
            电池不可拆卸
            充电器
            其他
            无线充电
            不支持无线充电
            电池容量（mAh）
            4000mAh（typ）/3900mAh（min）
            主体
            入网型号
            以官网信息为准
            品牌
            小米（MI）
            产品名称
            小米 红米Redmi K20 4800万超广角三摄 6GB+128GB 冰川蓝 全网通4G 双卡双待 全面屏拍照游戏智能手机
            上市年份
            2019年
            上市月份
            5月
            后置摄像头
            后摄的主摄像素
            4800万像素
            后摄主摄光圈
            f/1.75
            摄像头数量
            后置三摄
            闪光灯
            双LED灯
            数据接口
            数据传输接口
            其他
            耳机接口类型
            3.5mm
            充电接口类型
            Type-C
            NFC/NFC模式
            支持（卡模式）；支持卡模拟
            网络支持
            最大支持SIM卡数量
            2个
            网络频率（2G/3G）
            2G：GSM 850/900/1800/1900；3G：TD-SCDMA 1900/2000；3G：WCDMA 850/900/1900/2100；2G：GSM 900/1800；2G：GSM 900/1800/1900；3G：WCDMA：850/900/1700/1900/2100MHz
            5G网络
            不支持5G
            双卡机类型
            双卡双待单通
            4G网络
            4G TD-LTE(移动)；4G FDD-LTE(联通、电信)；4G FDD-LTE(联通)
            SIM卡类型
            Nano SIM
            3G/2G网络
            3G TD-SCDMA(移动)；3G WCDMA(联通)；3G CDMA2000(电信)；2G GSM(移动/联通)；2G CDMA(电信)
            主芯片
            CPU品牌
            高通(Qualcomm)
            CPU型号
            骁龙730
        </div>


<!--        <h3>{{ info.title }}</h3>-->

<!--        <hr>-->

<!--        <div class="content" v-html="info.content"></div>-->


    </div>
</template>

<script>
  export default {
    data() {
      return {
        info: {} // 图文数据
      };
    },
    created() {
      // this.getGoodsDesc();
    },
    methods: {
      // getGoodsDesc() {
      //   this.$http
      //     .get("api/goods/getdesc/" + this.$route.params.id)
      //     .then(result => {
      //       if (result.body.status === 0) {
      //         this.info = result.body.message[0];
      //       }
      //     });
      // }
    }
  };
</script>

<style lang="scss">
    .goodsdesc-container {
        padding: 4px;
        h3 {
            font-size: 16px;
            color: #226aff;
            text-align: center;
            margin: 15px 0;
        }
        .content{
            img{
                width: 100%;
            }
        }
    }
</style>
