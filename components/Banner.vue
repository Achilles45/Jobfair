<template>
    <section class="banner__wrapper container-fluid">
        <div class="container">
            <div class="row">
                <div class="col-md-5">
                    <h2>Find and Hire Top Talent For Your Software Projects </h2>
                    <p>Ulancer is an online marketplace for software developers and designers that allows you to get access to world class talents for all your projects need.</p>
                    <nuxt-link to="/hire" class="banner__btn signup__btn">Hire Talents Here <font-awesome-icon :icon="['fab', 'long-arrow-right']"  /></nuxt-link>
                </div>
                <div class="col-md-2"></div>
                <div class="col-md-5 d-none d-md-block">
                    <img src="../assets/images/user.png" class="img-fluid img" alt="">
                </div>
            </div>
        </div>
    </section>
</template>
<style lang="scss" scoped>
.banner__wrapper{
    padding: 5rem 0;
    margin-top: 4rem;
    background: #022B69;
    color: #fff;
    h2{
        font-weight: bold;
        padding-bottom: .9rem;
        padding-top: 4rem;
        letter-spacing: 1.5px;
        line-height: 3rem
    }
    p{
        opacity: .8;
        letter-spacing: 1px;
        font-size: .8rem;
        line-height: 1.5rem;
        padding-bottom: 1.5rem
    }
    .banner__btn{
        background: #FFF;
        padding: 1.1rem 3.5rem;
        border-radius: 3px;
        text-decoration: none;
        color: #273272;
    }
    .img{
        max-width: 370px;
        // height: auto;
    }
}
</style>