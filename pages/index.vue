<template>
  <div>
    <Cheader />
    <Cabout />
    <Cworks />
    <Cskill />
  </div>
</template>

<script>
import Cheader from "@/pages/-Cheader.vue"
import Cabout from '@/pages/-Cabout.vue'
import Cworks from '@/pages/-Cworks.vue'
import Cskill from '@/pages/-Cskill.vue'
export default {
  components: {
    Cheader,
    Cabout,
    Cworks,
    Cskill
  },
}
</script>

<style lang="scss" scoped>
</style>
