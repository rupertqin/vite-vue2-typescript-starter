<template>
  <div>
     {{ msg }}
  </div>
</template>

<script lang="ts">

export default {
  props: {
    msg: String,
  },
};
</script>

<style scoped lang="scss">
div {
  color: #42b983;
}
</style>