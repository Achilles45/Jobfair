<template>
  <div class="wrapper">
    <Navbar />
    <Banner />
    <Process />
    <Categories />
    <Freelancer />
    <Newsletter />
  </div>
</template>
<script>
import Navbar from '~/components/Navbar';
import Banner from '~/components/Banner';
import Process from '~/components/Process';
import Freelancer from '~/components/Freelancer';
import Categories from '~/components/Categories';
import Newsletter from '~/components/Newsletter';
export default {
  components:{
    Navbar,
    Banner,
    Process,
    Categories,
    Freelancer,
    Newsletter
  }
}
</script>
<style lang="scss" scoped>

</style>