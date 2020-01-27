<template>
    <section class="freelancer">
        <div class="container">
            <div class="row">
                <div class="col-md-6">
                    <img src="../assets/images/img3.svg" class="img-fluid img" alt="">
                </div>
                <div class="col-md-6">
                    <h3>Are You A World Class Designer or Software Developer?</h3>
                    <p>You can have access to over 500 executives who may need your services at zero promotion cost. You can get visible by creating a free account and updating your profile. We've got you coverred.</p>
                    <nuxt-link to="/" class="signin__btn">Get started here</nuxt-link>
                </div>
            </div>
        </div>
    </section>
</template>
<style lang="scss" scoped>
.freelancer{
    background: #022B69;
    padding: 7rem 0;
    color: #fff;
    h3{
        padding-top: 1rem;
        padding-bottom: 1rem
    }
    p{
        padding-bottom: 2rem;
        opacity: .8;
        font-size: .8rem;
        line-height: 1.5rem;
    }
    .signin__btn{
        background: #FFF;
        padding: 1.1rem 3.5rem;
        border-radius: 3px;
        text-decoration: none;
        color: #273272;
    }
    .img{
        max-width: 380px;
        height: auto;
    }
}
</style>