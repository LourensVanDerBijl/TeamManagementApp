<template>
  
  <!--heading page-->


      <div class="center">
        <div class="container">
          <div class="row text-center">
            <div class="col-md-6" id="loginRegisterForm">
              <div class="login" v-if="loginPage">
                <login></login>
              </div>

              <div class="register" v-if="registrationPage">
                <register></register>
              </div>

              <div class="adminLogin" v-if="adminPage">
                <adminlogin></adminlogin>
              </div>
            </div>

            <div class="col-md-6" id="personalD">
              <div class="vCenter">
                  <button type="button" class="btn btn-success" id="LoginButtons" @click="loginPage = true, registrationPage=false, adminPage=false">Login </button><br>
                  <button type="button" class="btn btn-primary" id="LoginButtons" @click="registrationPage = true, loginPage=false, adminPage=false">Register</button><br>
                  <button type="button" class="btn btn-danger" id="LoginButtons" @click="registrationPage = false, loginPage=false, adminPage=true">Admin Login</button><br>
              </div>
            </div>
            
          </div>
      </div>
      </div>
      

</template>

<script>
import login from './components/login.vue'
import register from './components/register.vue'
import adminlogin from './components/adminlogin.vue'

export default {
  name: 'App',
  data(){
    return{
      loginPage: true,
      registerPage: false,
      adminPage: false
    }
  },
  components: {
    login,
    register,
    adminlogin
    
  }
}
</script>


