<template>
  <h4 class="w-100 text-center text-black p-4 bg-secondary-subtle">
    Welcome {{ data.name }}, Branch: {{ data.branch }} - Track:
    {{ data.track }} - Governerate:
    {{ data.gov }}
  </h4>
</template>

<script>
export default {
  data: () => ({}),
  props: ["data"],
};
</script>

<style></style>
