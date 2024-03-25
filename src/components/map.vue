<template>
  <div class="vue-map-container" :class="$attrs.class">
    <div ref="vue-map" class="vue-map" :style="$attrs.style ? $attrs.style : ''"></div>
    <div class="vue-map-hidden">
      <slot></slot>
    </div>
    <slot name="visible"></slot>
  </div>
</template>

<script>
</script>
<style lang="scss">
</style>
