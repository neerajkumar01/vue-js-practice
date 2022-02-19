<template>
  <div>
    <div v-if="display">
      <h3>this is a file</h3>
    </div>
    <button v-on:click="clicks">clicks</button>
  </div>
</template>

<script>
export default {
  name: "ApiFileThis",
  data() {
    return {
      display: false,
    };
  },
  methods: {
    clicks() {
      this.display = !this.display;
    },
  },
};
</script>