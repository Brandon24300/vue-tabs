<template>
  <div class="vue-tabs__panel-container">
    <slot />
  </div>
</template>

<script>
export default {
  name: 'vue-tabs-item',
  props: {
    title: {
      type: String,
      required: true,
    },
    isDisabled: {
      type: Boolean,
      default: false,
    },
  },
};
</script>
