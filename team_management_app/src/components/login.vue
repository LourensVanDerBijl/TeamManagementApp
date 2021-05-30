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
    <input type="password" class="form-control" id="exampleInputPassword1" placeholder="Password" required><br>
  </div>

  <button type="submit" class="btn btn-success">Login</button>
</form>
</template>

<script>
export default {
  name: 'App'
}
</script>


