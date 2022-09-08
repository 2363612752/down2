<template>
  <a-card :bordered="false">
    
  </a-card>
</template>

<script>
import axios from 'axios'
export default {
    created(){
        axios.get('http://192.168.1.3:8081/captchaImage').then(res=>{
            console.log(res,'============');
        })
    }
}
</script>

<style>

</style>
