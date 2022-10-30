<template>
  <div class="landing">
    <section class="home">
      <div class="content">
        <div class="left">
          <nuxt-link to="" class="about_link">
            About us
          </nuxt-link>
          <div class="text">
            We will help you to orgonise your daily activities
          </div>
        </div>
        <div class="right">
          <div class="image">
          <img src="./../assets/image/Frame 162.svg" alt="" />
        </div>
        <h1>Create daily routine</h1>
        </div>
        <Card/>
      </div>
    </section>
  </div>
</template>

<script>
import Card from '~/components/card/index.vue';
export default {
  components:{
    Card,
  }
}
</script>

<style>
</style>