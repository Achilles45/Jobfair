<template>
    <nav class="mb-5">
        <div class="container">
            <div class="nav__contents d-flex justify-content-between align-items-center">
            <div class="navbar__brand pt-1">
                <h3> <font-awesome-icon :icon="['fas', 'cubes']"  /> <a href="/" class="logo">Ulancer</a></h3>
            </div>
            <ul class="navbar__items d-flex justify-content-between pt-3">
                <li><a href="">Become a Freelancer</a></li>
                <li><a href="">Hire a Freelancer</a></li>
                <li><a href="">Blog</a></li>
                <li><a href="">Find Jobs</a></li>
                <li><a href="">Post Jobs</a></li>
                <li><a href="">Sign Up</a></li>
                <li><a href="" class="signin">Sign In</a></li>
            </ul>
        </div>
        </div>
    </nav>
</template>
<script>
export default {
    name: 'Navbar'
}
</script>
<style lang="scss" scoped>
nav{
   padding: .7rem 0;
   width: 100%;
   position: fixed;
   background: #fff;
   z-index: 100;
   top: 0;
   .logo{
       font-weight: bold;
       color: #022B69;  
       text-decoration: none;
   }
   .fa-cubes{
       color: #022B69;
   }
   ul li a{
       padding-top: 2rem;
       color: #606060;
       padding: 0 .4rem;
       text-decoration: none;
   }
   .signin{
       background: #022B69;
       color: #fff;
       padding: 1rem 2rem;
       border-radius: 3px;
   }
}

//MEDIA QUERIES
@media only screen and (max-width: 600px){
    nav ul{
        display: none !important;
    }
}
</style>