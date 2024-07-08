<template>
  <div>
    <h1 class="title">Home Page</h1>
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
  name: "Home",
});
</script>

<style lang="scss" scoped>
/* Your styles here */
.title {
  color: $primary-color;
}
</style>
