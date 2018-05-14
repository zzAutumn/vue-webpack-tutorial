<template>
  <div>
    <h1>Please fill out our form...</h1>
    <form action="">
      <div id="form-header">
        <slot name="form-header"></slot>
      </div>
      <div id="form-fields">
          <slot name="form-fields"></slot>        
      </div>
      <div id="form-controls">
          <slot name="form-controls"></slot>        
      </div>
      <div id="useful-links">
        <ul>
          <li><a href="#">Link 1</a></li>
          <li><a href="#">Link 2</a></li>
          <li><a href="#">Link 3</a></li>
          <li><a href="#">Link 4</a></li>          
        </ul>
      </div>
            
    </form>
  </div>
</template>

<script>
  export default {

  }
</script>

<style>
  h1 {
    text-align: center;
  }

  #form-header,#form-fields,#form-controls,#useful-links {
    width: 100%;
    margin: 20px 0;
    padding: 10px 0;
    background: wheat;
  }

  #useful-links ul {
    list-style: none;
    display: flex;
    padding-left: 5px;
  }

  #useful-links ul li {
    margin-right: 20px;
  }



 

</style>