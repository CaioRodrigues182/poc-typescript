<template>
  <div class="home">
    <HelloWorld msg="Proof of Concept Treasy - Vue with Typescript" />
  </div>
</template>

<script>
import HelloWorld from "@/components/HelloWorld/index.vue";

export default {
  name: "home",
  components: {
    HelloWorld
  }
};
</script>
