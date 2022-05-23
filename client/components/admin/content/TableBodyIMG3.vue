<template>
  <td align="center" class="td-it">
    <img
      style="width: 100px"
      :src="`http://someUrl/api${img[keyImage]}`"
      alt=""
    />
  </td>
</template>

<script>
export default {
  props: {
    img: {
      //type: Image,
      required: true,
    },
    keyImage: {
      type: String,
      required: true,
    },
  },
};
</script>

<style scoped>
/* .td-it {
  max-width: 600px !important;
  padding: 0 30px 0px 0px !important;
} */
</style>
