<script>
export default {
  mounted() {
    this.$refs.ps.textContent = 'mounted!'
  }
}
</script>

<template>
  <p ref="ps">hello</p>
</template>
