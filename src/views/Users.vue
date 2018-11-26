<template>
    <div>
        <h1>User list</h1>
<!-- <HelloWorld v-bind:msg ="message"></HelloWorld> -->
<HelloWorld :msg ="message"></HelloWorld>
    </div>

</template>
<script>
import HelloWorld from "@/components/HelloWorld.vue";

export default {
  name: "home",
  components: {
    HelloWorld
  },
  data(){
      return{
          message:'Project 2'
      }
  }
};
</script>
