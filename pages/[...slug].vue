<template>
  <div>
   <h1>Whoops</h1>
  </div>
</template>

<script setup lang="ts">
// if (!page) {
throw createError({
  statusCode: 404,
  message: `Could not find content with route`,
  fatal: true,
});
// setResponseStatus(404)
// }
</script>
