<template>
  <!--Login -->
  <form>
   <div class="form-group">
    <label for="email" class="readText">Email address</label>
    <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp" placeholder="Enter email" required>
    <br>
  </div>
  <div class="form-group">
    <label for="password" class="readText">Password</label>
    <input type="password" class="form-control" id="exampleInputPassword1" placeholder="Password" required>
  </div>
  <div class="form-check">
    <br>
  </div>
  <button type="submit" class="btn btn-success">Login</button>
</form>





</template>

<script>
//import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    
  }
}
</script>

<style>

</style>
