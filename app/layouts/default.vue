<template>
  <div>
    <TheHeader />
    <div class="wrapper">
      <nuxt class="container" />
    </div>
  </div>
</template>

<script>
import TheHeader from '~/app/components/TheHeader.vue'

export default {
  components: {
    TheHeader
  }
}
</script>
