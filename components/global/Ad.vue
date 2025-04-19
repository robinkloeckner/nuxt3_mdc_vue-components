<script setup>
const props = defineProps({cssClass: String});
</script>

<template>
  <div class="ad" :class="props.cssClass">
    <div class="ad-header">Ad: <MDCSlot unwrap="p,div" /></div>
    <div class="ad-banner">Place you ad here.</div>
  </div>
</template>

<style scoped>
.ad {
  border: 1px solid #eeeeee;
  border-radius: 5px;
  padding: 10px;
}

.ad-header {
  font-size: 10px;
}

.ad-banner {
  background-color: #eeeeee;
  border: 1px solid #eeeeee;
  border-radius: 5px;
  padding: 10px;
}

.info {
  border-color: orange !important;
}
</style>
