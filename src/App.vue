<template>
  <div>
    <my-addaction></my-addaction>
    <p>------------------------------</p>
    <my-subtracaction></my-subtracaction>
  </div>
</template>
<script>
import AddAction from './components/AddAction.vue'
import Subtracaction from './components/subtracaction.vue'
export default {
  data() {
    return {}
  },
  components: {
    'my-addaction': AddAction,
    'my-subtracaction': Subtracaction,
  },
}
</script>
<style lang="less" scoped>
div {
  color: red;
}
</style>