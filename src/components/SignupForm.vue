<template>
  <form>
    <label>Email</label>
    <input type="email" required v-model="email">
    <label>Password</label>
    <input type="password" required v-model="password">
  </form>
  <p>Email: {{ email }}</p>
  <p>Password: {{ password }}</p>
</template>
<script>
  export default {
    data() {
      return {
        email: '',
        password: '',
      }
    }

  }
</script>
<style>
</style>