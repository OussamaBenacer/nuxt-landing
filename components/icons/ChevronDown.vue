<script setup>
defineProps({
  width: {
    type: String,
    default: "18",
  },
  className: {
    type: String,
    default: "",
  },
});
</script>
<template>
  <svg
    :width="width"
    :height="width / 2"
    viewBox="0 0 17 9"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
    :class="className"
  >
    <path
      fill-rule="evenodd"
      clip-rule="evenodd"
      d="M0.79289 1.70711C0.40237 1.31658 0.40237 0.68342 0.79289 0.29289C1.18342 -0.09763 1.81658 -0.09763 2.20711 0.29289L8.5 6.5858L14.7929 0.29289C15.1834 -0.09763 15.8166 -0.09763 16.2071 0.29289C16.5976 0.68342 16.5976 1.31658 16.2071 1.70711L9.2071 8.7071C8.8166 9.0976 8.18342 9.0976 7.79289 8.7071L0.79289 1.70711Z"
      fill="currentColor"
    />
  </svg>
</template>
