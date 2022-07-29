<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg = "Bienvenue sur l'interface de connexion" />
  <LoginForm />
  <ForgotPassword />
  <SignIn />

</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import LoginForm from './components/LoginForm.vue'
import ForgotPassword from './components/ForgotPassword.vue'
import SignIn from './components/SignIn.vue'


export default {
  name: 'App',
  components: {
    LoginForm,
    HelloWorld,
    ForgotPassword,
    SignIn
}
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
