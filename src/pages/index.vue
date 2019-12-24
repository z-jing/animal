<template>
    <div class="home">
        <img width="100%" src="@/assets/images/banner.png" alt="">
        <!--<div class="example_exhibit">-->
            <!--<div>-->
                <!--<img src="@/assets/images/index-img-1.jpg" alt="">-->
                <!--<p>處方.指示用藥</p>-->
            <!--</div>-->
            <!--<div>-->
                <!--<img src="@/assets/images/index-img-2.jpg" alt="">-->
                <!--<p>機能食品</p>-->
            <!--</div>-->
            <!--<div>-->
                <!--<img src="@/assets/images/index-img-3.jpg" alt="">-->
                <!--<p>醫材.用品</p>-->
            <!--</div>-->
        <!--</div>-->
        <div class="about_us">
            <Row class="about_us_box">
                <Col span="11">
                <h2 class="about_us_title">寵物自用品</h2>
                <span class="about_us_text">ABOUT US</span>
                <div class="about_us_content">
                    <h3>店铺的商品每一款都有它存在的理由</h3>
                    <h3>放心给自家两狗一猫食用使用的才售卖</h3>
                    <h4>关于包邮:</h4>
                    <p>“免运费”宝贝一起发出包邮,或者全场买满99包邮</p>
                    <p>(系统未减去运费联系客服哦,偏远地区或者超重需补差价)</p>
                    <p style="font-size: 14px;color: #000">
                        宝贝详情:谢谢你花时间了解它<br/>
                        “泪痕”一相信宠物这个问题也困扰很多家长<br/>
                        不仅仅是影响宝贝的颜值,长期有泪痕还会引起眼部健康皮肤,
                        感染,散发臭味等等。市面上的泪痕产品也有很多,
                        这款是目前尝试过了解过效果很好的产品,
                        大部分家长反馈有效率高。<br/>
                        纯植物萃取,安全温和也是选择它的原因;
                        两个月以上猫狗就可以使用,
                        建议一瓶改善,两瓶巩固,
                        10kg以下体重一天一管,轻松喂食。
                    </p>
                </div>
                </Col>
                <Col span="11" offset="2">
                <img width="100%" src="@/assets/images/logowithback.png" alt="">
                </Col>
            </Row>
        </div>
    </div>
</template>
<script>
    export default {
        props: {

        },
        data () {
            return {

            }
        },
        mounted(){

        },
        methods: {

        }
    }
</script>
<style lang="scss" scoped>
     .example_exhibit,.about_us_box {
         width: 85%;
         margin: 25px auto;
     }
    .example_exhibit {
        display: flex;
        justify-content: space-between;
        padding: 60px 0;
        &>div{
            display: inline-block;
            width: 28%;
            text-align: center;
        }
        img{
            width: 350px;
            height:260px;
        }
        p{
            font-size: 20px;
            margin-top: 10px;
        }
    }
    .about_us {
        background-color: #f7f8f8;
        padding: 20px 0;
    }
    .about_us_title {
        font-size: 26px;
        margin-bottom: 10px;
    }
    .about_us_text {
        border-bottom: 2px solid $themeColor;
        margin-bottom: 10px;
        display: inline-block;
        font-size: 18px;
        color: #b3afaf;
        padding-bottom: 10px;
    }
    .about_us_content {
        line-height: 2.5;
        font-size: 16px;
    }
</style>
