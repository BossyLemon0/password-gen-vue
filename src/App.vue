<template>
  <div class="main">
    <Modals/>
    <Password/>
    <Button/>
  </div>
</template>

<script>
import Modals from './components/Modals.vue';
import Password from './components/Password.vue';
import Button from './components/Button.vue'

export default {
  name: 'App',
  components: {
    Modals,
    Password,
    Button
  }
}
</script>

<style>
.main{
  height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
}
</style>

