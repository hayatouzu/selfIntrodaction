<template>
  <div>
    <Cheader />
    <section id="about" class="about"></section>

    <section class="works"></section>

    <section id="contact" class="contact"></section>
  </div>
</template>

<script>
import Cheader from "@/pages/-Cheader.vue"
export default {
  components: {
    Cheader,
  },
}
</script>

<style lang="scss" scoped>
.about {
  height: 100vh;
  background-color: #ffffff;
}

.works {
  height: 100vh;
  background-color: #383634;
}

.contact {
  height: 100vh;
  background-color: rgba(25, 25, 120, 0.9);
}
</style>
