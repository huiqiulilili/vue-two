<template>
  <div class="container">
    <Category/>
    <Category/>
    <Category/>
  </div>
</template>

<script>
import Category from "./components/Category";

export default {
  name: 'App',
  components:{Category},
  data() {
    return {
        foods:[]
    }
  }
}
</script>

<style>
.container{
  display: flex;
  justify-content: space-around;
}

</style>
