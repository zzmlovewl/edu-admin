<template>
  <div id="app">
    <router-view/>
  </div>
</template>
<script>
// import request from '@/utils/request'
// request({
//   method: 'get',
//   url: '/front/ad/getAdList'
//   // url: '/boss/v2/api-docs?group=edu-boss-boot'
// }).then(res => {
//   console.log(res)
// })
export default {
  name: 'App'
  // provide () {
  //   return {
  //     reload: this.reload
  //   }
  // },
  // data () {
  //   return {
  //     isReouterAlive: true
  //   }
  // },
  // methods: {
  //   reload () {
  //     this.isReouterAlive = false
  //     this.$nextTick(function () {
  //       this.isReouterAlive = true
  //     })
  //   }
  // }
}
</script>
<style lang="scss"></style>
