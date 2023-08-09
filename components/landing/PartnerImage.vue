<template>
    <div class="mx-10 max-sm:mx-0">
      <img :src="require(`~/assets/img/partner/${img}`)" class=" lg:w-32" alt="" />
    </div>
</template>
<script>
export default {
  props: {
    img: {
      type: String,
      default: '',
    },
  },
}
</script>
