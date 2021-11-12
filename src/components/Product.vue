<template>
  <div class="singolo">
    <img :src="image" alt="" />
    <h5>{{ series }}</h5>
  </div>
</template>

<script>
export default {
  props: {
    image: String,
    series: String,
  },
};
</script>

<style>
.singolo {
  width: 140px;
  margin: 10px;
}
img {
  width: 140px;
  height: 140px;
}
h5 {
  color: white;
  font-weight: lighter;
}
</style>