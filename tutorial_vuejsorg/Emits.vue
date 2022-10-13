<script>
import ChildComp from './ChildComp2.vue'

export default {
  components: {
    ChildComp
  },
  data() {
    return {
      childMsg: 'No child msg yet',
      message: 1
    }
  }
}
</script>

<template>
  <ChildComp @response1="(msg) => childMsg = msg"/>
  <p>{{ childMsg }}</p>
</template>