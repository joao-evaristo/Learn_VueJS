<script>
import ChildComp from './ChildComp3.vue'

export default {
  components: {
    ChildComp
  },
  data() {
    return {
      msg: 'from parent'
    }
  }
}
</script>

<template>
  <ChildComp>{{msg}}</ChildComp>
</template>