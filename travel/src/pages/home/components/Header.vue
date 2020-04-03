<template>
    <div class="header">
        <div class="header-left">
            <div class="iconfont back-icon">
                &#xe720;
            </div>
        </div>
        <div class="header-input">
             <span class="iconfont">
                &#xe741;
            </span>
            输入城市景点/游乐主题
            </div>
        <div class="header-right ">
            城市
            <span class="iconfont">
                &#xe749;
            </span>
        </div>

    </div>
</template>

<script>
export default {
  name: 'HomeHeader'
}
</script>
<style lang="stylus" scoped>
@import '~styles/varibles.styl'
    .header
        display flex
        line-height .86rem
        background $bgColor
        color #fff
        .header-left
            width .64rem
            float left
            .back-icon
                text-align  center
                font-size .4rem
        .header-input
            flex  1
            height .64rem
            line-height .64rem
            margin-top .12rem
            padding-left .2rem
            margin-left .2rem
            background #fff
            border-radius .1rem
            color #ccc
        .header-right
            widows 1.24rem
            float right
            text-align center

</style>
