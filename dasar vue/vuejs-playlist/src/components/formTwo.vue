<template lang="html">
  <div>
    <form-helper>
      <div slot="form-header">
        <h3>Form Two - login In</h3>
        <p>Enter your details to log-in</p>
      </div>
      <div slot="form-fields">
        <input type="text" placeholder="username" required>
        <input type="password" placeholder="password" required>
      </div>
      <div slot="form-controls" >
        <button v-on:click="handleSumbit">Login</button>
      </div>
    </form-helper>
  </div>
</template>

<script>
import formHelper from './formHelper.vue';
export default {
  components:{
    'form-helper':formHelper
  },
  data(){
    return{
    }
  }
}
</script>

<style lang="css">
</style>
