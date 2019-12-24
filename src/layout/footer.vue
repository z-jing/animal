<template>
    <div class="footer">
        <div class="footer_content">
            <section class="footer_logo">
                <h2>寵物自用品</h2>
            </section>
            <section class="footer_describe">
                <Row>
                    <Col span="15">
                    <h3>店铺的商品每一款都有它存在的理由</h3>
                    <h3>放心给自家两狗一猫食用使用的才售卖</h3>
                    </Col>
                    <Col span="6" offset="2">
                    <div><Icon type="md-bookmark" /> 華盛行貿易有限公司</div>
                    <div><Icon type="md-pin" /> 中g台台中市太平來二街12-1號</div>
                    <div><Icon type="md-call" /> tel：+866915378819</div>
                    </Col>
                </Row>
            </section>
            <h3 class="about_us"><router-link to="/aboutUs">關於我們</router-link></h3>
        </div>
        <div class="copyright">
            <span>Copyright © 2019 寵物自用品 All Rights Reserved.</span>
        </div>
    </div>
</template>
<style lang="scss" scoped>
    .footer_content {
        background-color: $themeColor;
        color: #fff;
    }
    .footer_logo,.footer_describe,.about_us {
        width: 85%;
        margin: auto;
        padding: 20px 0;
        font-size: 16px;
    }
    .footer_describe {line-height: 2}
    .copyright {
        background-color: #3d454b;
        line-height: 2.5rem;
        color: #fff;
        span {
            width: 85%;
            display: block;
            margin: auto;
        }
    }
    .about_us{
        font-size: 16px;
        a{
            color: #fff;
            /*line-height: 100px;*/
        }
    }
</style>
