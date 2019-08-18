<template>
    <div>

        <!--轮播图区域-->
        <mt-swipe :auto="4000">
            <mt-swipe-item>1</mt-swipe-item>
            <mt-swipe-item>2</mt-swipe-item>
            <mt-swipe-item>3</mt-swipe-item>
        </mt-swipe>
    </div>
</template>

<script>

</script>

<style lang="scss" scoped>
.mint-swipe {
    height: 200px;

    .mint-swipe-item {
        &:nth-child(1) {
            background-color: #1b6d85;
        }
        &:nth-child(2) {
            background-color: #dd524d;
        }
        &:nth-child(3) {
            background-color: #398439;
        }
    }
}
</style>