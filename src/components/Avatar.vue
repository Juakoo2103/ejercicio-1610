<template>
  <img
    :src="url"
    :style="{ width: tamaño + 'px', height: tamaño + 'px' }"
    class="rounded-circle"
  />
</template>

<script>
export default {
  props: {
    url: {
      type: String,
      required: true,
    },
    tamaño: {
      type: Number,
      required: true,
    },
  },
};
</script>
