<template>
  <div>
    <h1>大佬峰，带我飞ooo</h1>
    <img src="~@/assets/1.jpeg">
    <img src="~@/assets/4.png">
    <img src="~@/assets/2.jpeg">
    <img src="~@/assets/3.jpeg">
  </div>
</template>

<style>
  img{
    display: block;
  }
</style>
<!-- <script>
  export default {
    name: 'index',
    data () {
      return {
        musics: []
      }
    },
    mounted () {
      let request = new XMLHttpRequest()
      request.open('get', 'https://api.1bgm.com/musics/tags', true)
      request.setRequestHeader('Accept', 'application/json')
      request.setRequestHeader('Content-Type', 'application/json')
      request.send()
      if (request.status === 200) {
        this.musics = request.response.name
      }
    }
  }
</script> -->