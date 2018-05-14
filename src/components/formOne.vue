<template>
  <formHelper>
    <div slot="form-header">
      <h3>Form One - Contact Us</h3>
      <p>Fill in this form to contact us</p>
    </div>
    <div slot="form-fields">
      <input type="text" placeholder="name" required>
      <label for="name">Your Message:</label>
      <textarea name="msg" id="msg" cols="30" rows="5"></textarea>
    </div>
    <div slot="form-controls">
      <button v-on:click="handleSubmit">Send</button>
    </div>
  </formHelper>
</template>

<script>
import formHelper from './formHelper';
export default {
  components: {
    'formHelper': formHelper,
  },
  data(){
    return {

    }
  }
}
</script>

<style>

</style>