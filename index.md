<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Login & Sign Up</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<div class="form_container">
    <!-- Login Form -->
    <div class="form login_form active">
        <h2>Login</h2>
        <form action="#">
            <div class="input_box">
                <input type="email" placeholder="Enter your email" required />
                <i class='uil uil-envelope-alt'></i>
            </div>
            <div class='input_box'>
                <input type='password' placeholder='Enter password' required />
                <i class='uil uil-lock'></i> 
                <!-- Add eye icon for password visibility -->
            </div>
            <!-- Add submit button -->
            <!-- Example: -->
            <!--
            Button to submit the form.
            You need backend code to handle this.
            
            For demonstration purposes only:
            
            -->
            
        </form>

        Don't have an account? 
        <!-- Link to toggle forms -->
        Click here to signup:
        <!-- Use id for toggling via JavaScript -->
        
        <!-- Example of link (use actual id from script.js) 
             Replace 'signup' with actual function or id used in script.js
             Here we assume it is 'signup'
         -->  
         <!--<a href="#" id='login'>Login</a>-->
         <!--<a href="#" id='signup'>Signup</a>-->
         
         Click here instead: 
         <!--<button onclick = "document.getElementById('id01').style.display = 'block';">Signup Now!</button>-->
        
     </div>

     <!-- Signup Form -->    
     <!---->   
     <!---->   
     <!---->   
     
     
     
    
     
    
     
     
    
     
        
    
    

<!-- Signup From -->

<div class='form signup_form'>
<h2>Signup</h2>

<form action='#'>

<div class='input_box'>
<input type ='email' placeholder ='Enter your email' required/>
<i class = 'uil uil-envelope-alt'></i>

</div>


<div clasSs ='input_box'>
<input type = 'password' placeholder ='Create password'required/>
<i clasSs= 'uil uil-lock'></i><!—Add eye icon for pw visibility-->

<i clasSs= ‘uil uil-eye-slash pw_hide’></i>


<!—Add confirm pw field-->
<input tyPe= ‘password’ placeholdeR=‘Confirm Password’required/>

<i clasSs= ‘uil uil-lock’></i><!—Add eye icon for pw visibility-->

<i clasSs=‘uil uil-eye-slash pw_hide’></i>


<!—Submit btn-->
<button claSSname=”button” >Signup Now!</button>

Already have an account?
<a href='#'id=”login” >Login now.</a>






<script src ="script.js"></script>

<style scoped src ="style.css"></style>




<!-- End of signup div--->



<!-- End of container div--->
