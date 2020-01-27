<template>
    <section class="process__wrapper">
        <div class="container">
            <div class="row">
                <div class="col-md-3"></div>
                <div class="col-md-6 text-center heading">
                    <h4>You're four steps away from hiring top talent</h4>
                </div>
                <div class="col-md-3"></div>
            </div>
                <div class="process__content">
                    <div class="process__card text-center">
                        <img src="../assets/images/register.svg" class="img-fluid process__img" alt="">
                        <h5>Create Account</h5>
                        <p>Begin the process of hiring world class talents by creating a free account. It is free and easy to do.</p>
                    </div>
                     <div class="process__card text-center">
                        <img src="../assets/images/note.svg" class="img-fluid process__img" alt="">
                        <h5>Post Job</h5>
                        <p>Fill in a detailed description and requirements of the job you need to get done.</p>
                    </div>
                     <div class="process__card text-center">
                        <img src="../assets/images/people.svg" class="img-fluid process__img" alt="">
                        <h5>Interview Candidates</h5>
                        <p>Schedule interview with the candidates that reached out to you to see if there is a match.</p>
                    </div>
                    <div class="process__card text-center">
                        <img src="../assets/images/hire.svg" class="img-fluid process__img" alt="">
                        <h5>Hire</h5>
                        <p>Once satified with a candidate performance, hire and remove that job listing.</p>
                    </div>
                </div>
        </div>
    </section>
</template>
<style lang="scss" scoped>
.process__wrapper{
    padding: 6rem 0;
    background: #F8F8F8;
    .heading h4{
        color: #000;
        text-transform: capitalize;
    }
    .process__content{
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
        grid-gap: 20px;
        padding-top: 2.5rem;
        .process__card{
            // box-shadow: 3px 3px 3px 0px rgba(0,0,0,.10);
            padding: 1rem;
            border-radius: 3px;
            .process__img{
                max-width: 40px;
                height: auto;
            }
            h5{
                padding-top: 1rem;
                padding-bottom: .5rem;
                color: #000;
                font-size: 1rem;
            }
            p{
                color: #404040;
                font-size: .9rem;
                // letter-spacing: .7px;
            }
        }
    }
}
</style>