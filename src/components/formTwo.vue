<template>
  <formHelper>
    <div slot="form-header">
      <h3>Form Two - Log In</h3>
      <p>Enter your details to log-in</p>
    </div>
    <div slot="form-fields">
      <input type="text" placeholder="username" required>
      <input type="password" placeholder="password" required>
    </div>
    <div slot="form-controls">
      <button v-on:click="handleSubmit">Login</button>
    </div>
  </formHelper>
</template>

<script>
import formHelper from './formHelper';
export default {
  components: {
    'formHelper': formHelper,
  }
}
</script>

<style>

</style>