<template>
    <section class="newsletter__wrapper container-fluid">
        <div class="contianer">
            <div class="row">
                <div class="col-md-2"></div>
                <div class="col-md-8">
                    <div class="heading text-center">
                        <h4>Subscribe to Our Newsletter to Stay in the Loop</h4>
                    </div>
                    <div class="row">
                        <div class="col-md-3"></div>
                        <div class="col-md-6">
                            <form action="" class="d-flex justify-content-between">
                        <input type="text" class="form-control" placeholder="Enter email address" name="email">
                        <button type="submit" class="newsletter__btn">Subscribe</button>
                    </form>
                        </div>
                        <div class="col-md-3"></div>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>
<style lang="scss" scoped>
.newsletter__wrapper{
    padding: 5rem 0;
    form{
        margin-top: 2rem;
        input{
            height: 3rem;
            box-shadow: none;
            border-radius: 0px;
        }
        .newsletter__btn{
            background: #022B69;
            padding: 0rem 3rem;
            border-radius: 0px;
            height: 3rem;
            border: none;
            color: #fff;
        }
    }
}
</style>