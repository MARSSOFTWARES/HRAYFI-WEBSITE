<template>
  <div class="about">
    <h1>{{ pageName}}</h1>
    <p v-bold>{{ pageDescription }}</p>
  </div>
</template>

<script>
export default {
  data: function () {
  return {
    pageName : "About Us",
    pageDescription : 'This is Abous Us Page',
  }
  },
  name: "about",
};
</script>
