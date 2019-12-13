<template>
  <div class="login">
      <hmbutton text="登录" @click="login"></hmbutton>
  </div>
</template>

<script>
import hmbutton from '@/components/hm_button.vue'
export default {
  components: {
    hmbutton
  },
  methods: {
    login () {
      console.log('111')
    }
  }
}
</script>

<style>

</style>
