<template>
  <button class="test">
    <slot />
  </button>
</template>

<script>
export default {
  name: 'empty',

  props: {
    color: String,
    type: {
      type: String,
      default: 'primary',
    },
  },
};
</script>

<style lang="less">
.test {
  min-width: 120px;
  color: #fff;
  font-size: 16px;
  line-height: 36px;
  background-color: orange;
  border: none;
  border-radius: 30px;
}
</style>
