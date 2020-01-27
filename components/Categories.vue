<template>
    <section class="category container-fluid">
        <div class="container">
            <div class="row">
                <div class="col-12 text-center">
                    <h4>Job Categories</h4>
                </div>
            </div>
           <div class="row">
               <div class="col-md-2"></div>
               <div class="col-md-8">
                    <div class="categories__wrapper">
                <div class="categories__card">
                    <img src="../assets/images/img5.svg" class="img-fluid img" alt="">
                    <h5>Frontend</h5>
                </div>
                 <div class="categories__card">
                    <img src="../assets/images/img5.svg" class="img-fluid img" alt="">
                    <h5>Backend</h5>
                </div>
                 <div class="categories__card">
                    <img src="../assets/images/img5.svg" class="img-fluid img" alt="">
                    <h5>Fullstack</h5>
                </div>

                 <div class="categories__card">
                    <img src="../assets/images/img5.svg" class="img-fluid img" alt="">
                    <h5>Devops</h5>
                </div>
                 <div class="categories__card">
                    <img src="../assets/images/img5.svg" class="img-fluid img" alt="">
                    <h5>Project Manager</h5>
                </div>
                 <div class="categories__card">
                    <img src="../assets/images/img5.svg" class="img-fluid img" alt="">
                    <h5>Designer</h5>
                </div>
            </div>
               </div>
               <div class="col-md-2"></div>
           </div>
        </div>
    </section>
</template>
<style lang="scss" scoped>
.category{
    padding: 7rem 0;
    .categories__wrapper{
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(100px, 1fr));
        grid-gap: 20px;
        padding-top: 2.5rem;
        .categories__card{
            text-align: center;
            box-shadow: 0px 3px 3px rgba(0,0,0,.10);
            padding: .5rem;
            h5{
                color: #606060;
                font-size: .9rem;
                padding-top: .5rem
            }
            .img{
                max-width: 30px;
                height: auto;
            }
        }
    }
}
</style>