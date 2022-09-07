<template>
<div class='page'>
  <div class="column container">
    <form>
      <div class="section">Sign In</div>
      <div class="spacer-04"></div>
      <input class="sign-in" type='email' placeholder = "Email Address" v-bind = "password"/>
      <div class="spacer-02"></div>
      <input type='password' placeholder = "Password" v-bind = "password"/>
      <div class="spacer-04"></div>
      <div class="row justify-center align-center">
        <NuxtLink class = 'btn-outline-primary' to='/profile'>Sign In</NuxtLink>
        <div class='spacer-wide-02'></div>
        <NuxtLink class = 'btn-outline-secondary' to = '/register'>Register</NuxtLink>
        </div>
    </form>
  </div>
    
  </div>
</template>

<script>
export default {}
</script>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family:
    'Quicksand',
    'Source Sans Pro',
    -apple-system,
    BlinkMacSystemFont,
    'Segoe UI',
    Roboto,
    'Helvetica Neue',
    Arial,
    sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
nav {
  display: flex;
  justify-content: space-between;
  height: 90px;
  width: 100vw;
  background: var(--white);
  box-shadow: var(--elevation-02);
  position: fixed;
  top: 0;
  left: 0;
  align-items: center;
}
.section {
  font-size: var(--section);
  font-family: 'Montserrat', Sans-Serif;
  color: var(--gray--700);
  letter-spacing: 3px;
  word-spacing: 5px;
}
.page {
  background: linear-gradient(150deg, #98CBD9 0%, #EDF8FB 100%);
}
</style>
