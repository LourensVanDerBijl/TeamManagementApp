<template>
  
  
  <!--Registration -->
 <form>
    <div class="form-group">



    <div class="container">
      <div class="row">
        <div class="col-sm-6">
          <label for="name" class="readText">Name: </label>
          <input type="text" class="form-control" id="name" placeholder="Enter your name" required>
          <br>
          <label for="surname" class="readText">Surname:</label>
          <input type="text" class="form-control" id="surname" placeholder="Enter your surname" required>
          <br>
          <label for="company" class="readText">Company Name:</label>
          <input type="email" class="form-control" id="exampleInputEmail1"  placeholder="Enter the name of your company" required>
          <br>
          <label for="Address" class="readText">Company address</label>
          <input type="email" class="form-control" id="companyAddress" placeholder="Enter your company Address" required>
          <br>
        </div>
    
        <div class="col-sm-6">
           <label for="industry" class="readText">Company Industry</label>
            <select class="form-control" id="CompanyIndustry">
              <option>Contruction</option>
              <option>Telecommunication</option>
              <option>Minning</option>
              <option>Engineuring</option>
            </select>
            <br>
          <label for="Address" class="readText">Company address</label>
            <input type="email" class="form-control" id="companyAddress" placeholder="Enter your company Address" required>
            <br>
          <label for="email" class="readText">Email address</label>
            <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp" placeholder="Enter email" required>
            <br>
          <label for="password" class="readText">Password</label>
            <input type="password" class="form-control" id="exampleInputPassword1" placeholder="Password" required>
          </div>
          <button type="submit" class="btn btn-primary">Register</button>
        </div>
      </div>
    </div>



    
    
   


    
</form>


</template>

<script>


export default {
  name: 'App'
  
}
</script>
