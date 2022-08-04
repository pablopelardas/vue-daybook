<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <button @click='goToDaybook' class="btn btn-primary">1</button>
    <button @click='goToDaybook' class="btn btn-secondary">2</button>
    <button @click='goToDaybook' class="btn btn-success">3</button>
  </div>
</template>

<script>
export default {
  methods:{
    goToDaybook(){
      this.$router.push({ name: 'no-entry' });
    }
  }
}
</script>