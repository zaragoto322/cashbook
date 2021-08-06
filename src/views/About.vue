<template>
  <div class="about">
    <h1>This is an about page</h1>
    <x />
  </div>
</template>

<script lang="ts">
import x from '@/components/Test.vue'
export default {
  name: 'About',
  components: {
    x
  }
}
</script>
