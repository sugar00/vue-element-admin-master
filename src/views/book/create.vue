<template>
  <Detail :is-edit="false" />
</template>

<script>
import Detail from './components/Detail'

export default {
  name: 'CreateBook',
  components: { Detail }
}
</script>
<style lang='scss' scoped>
</style>
