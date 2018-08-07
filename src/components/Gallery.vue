<template>
  <div class="Gallery">
    TBD
    {{ rowsCount }}
  </div>
</template>

<script>
  export default {
    name: 'Gallery',
    props: {
      // msg: String
    },
    data: () => {
    const rowsCount = 3

    return {
      rowsCount
    }
  },
  }
</script>

<style scoped lang="scss">

</style>

