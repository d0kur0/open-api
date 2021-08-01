<template>
  <div class="open-api">Open Api component</div>
</template>

<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
  name: "App",
  components: {},
});
</script>

<style lang="scss">
.open-api {
  border: 3px dashed rgb(119, 178, 255);
  border-radius: 10px;
  color: rgb(36, 131, 255);
  background-color: rgb(228, 247, 255);
  height: 450px;
  font-size: 3em;
  display: flex;
  align-items: center;
  justify-content: center;
  font-family: sans-serif;
}
</style>
