<template>
  <a :href="`https://www.youtube.com/watch?v=${id}`">https://www.youtube.com/watch?v={{ id }}</a>
</template>

<script>
export default {
  props: ["id"],
};
</script>
