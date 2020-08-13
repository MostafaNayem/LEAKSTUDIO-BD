<html>
  <head>   
  <meta name="viewport" content="width=device-width,initial-scale=1,maximum-scale=1"/>
  <title> NCash - Login </title>
  
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
  <style type="text/css">
   
  body {
  background: #f9f9f9; /* fallback for old browsers */
  font-family: "Raleway", sans-serif;
  color: #151515;
  }
  a {
  color: black;
  font-weight: 600;
  font-size: 0.85em;
  text-decoration: none;
  }
  label {
  color: black;
  font-weight: 600;
  font-size: 0.85em;
  }
  input:focus {
  outline: none;
  }
  .container {
  display: flex;
  align-items: center;
  justify-content: center;
  height: 100vh;
  }
  .form {
  display: flex;
  width: auto;
  background: #fff;
  margin: 15px;
  padding: 25px;
  border-radius: 25px;
  box-shadow: 0px 10px 25px 5px #0000000f;
  }
  .sign-in-section {
  padding: 15px;
  }
  .sign-in-section h6 {
  margin-top: 0px;
  font-size: 0.75em;
  }
  .sign-in-section h1 {
  text-align: center;
  font-weight: 700;
  position: relative;
  }
  .sign-in-section h1:after {
  position: absolute;
  content: "";
  height: 5px;
  bottom: -15px;
  margin: 0 auto;
  left: 0;
  right: 0;
  width: 40px;
  background: #7F00FF;
  background: -webkit-linear-gradient(to right, #E100FF, #7F00FF);
  background: linear-gradient(to right, #E100FF, #7F00FF);
  -o-transition: 0.25s;
  -ms-transition: 0.25s;
  -moz-transition: 0.25s;
  -webkit-transition: 0.25s;
  transition: 0.25s;
  }
  .sign-in-section h1:hover:after {
  width: 100px;
  }
  .sign-in-section ul {
  list-style: none;
  padding: 0;
  margin: 0;
  text-align: center;
  }
  .sign-in-section ul > li {
  display: inline-block;
  padding: 10px;
  font-size: 15px;
  width: 20px;
  text-align: center;
  text-decoration: none;
  margin: 5px 2px;
  border-radius: 50%;
  box-shadow: 0px 3px 1px #0000000f;
  border: 1px solid #e2e2e2;
  }
  .sign-in-section p {
  text-align: center;
  font-size: 0.85em;
  }
  .form-field {
  display: block;
  width: 250px;
  margin: 10px auto;
  }
  .form-field label {
  display: block;
  margin-bottom: 10px;
  }
  .form-field input[type="email"],
  input[type="password"] {
  width: -webkit-fill-available;
  padding: 15px;
  border-radius: 10px;
  border: 1px solid #e8e8e8;
  }
  .form-field input::placeholder {
  color: #e8e8e8;
  }
  .form-field input:focus {
  border: 1px solid #AE00FF;
  }
  .form-field input[type="checkbox"] {
  display: inline-block;
  }
  .form-options {
  display: block;
  margin: auto;
  width: 250px;
  }
  .checkbox-field {
  display: inline-block;
  float: left;
  }
  .form-options a {
  float: right;
  text-decoration: none;
  }
  .btn {
  padding: 15px;
  font-size: 1em;
  width: 100%;
  border-radius: 25px;
  border: none;
  margin: 20px 0px;
  }
  .btn-signin {
  cursor: pointer;
  background: #7F00FF;
  background: -webkit-linear-gradient(to right, #E100FF, #7F00FF);
  background: linear-gradient(to right, #E100FF, #7F00FF);
  box-shadow: 0px 5px 15px 5px #840fe440;
  color: #fff;
  }
  .links a:nth-child(1) {
  float: left;
  }
  .links a:nth-child(2) {
  float: right;
  }
  
   </style>
   <style type="text/css">
   .popup .overlay {
   position:fixed;
   top:0px;
   left:0px;
   width:100vw;
   height:100vh;
   background:rgba(0,0,0,0.7);
   z-index:1;
   display:none;
   }
   
   .popup .content {
   position:absolute;
   top:50%;
   left:50%;
   transform:translate(-50%,-50%) scale(0);
   background:#fff;
   width:300px;
   height:250px;
   z-index:2;
   text-align:center;
   padding:20px;
   box-sizing:border-box;
   font-family:"Open Sans",sans-serif;
   }
   
   .popup .close-btn {
   cursor:pointer;
   position:absolute;
   right:20px;
   top:20px;
   width:30px;
   height:30px;
   background:#222;
   color:#fff;
   font-size:25px;
   font-weight:600;
   line-height:30px;
   text-align:center;
   border-radius:50%;
   }
   
   .popup.active .overlay {
   display:block;
   }
   
   .popup.active .content {
   transition:all 300ms ease-in-out;
   transform:translate(-50%,-50%) scale(1);
   }
   
   button {
   position:absolute;
   top:50%;
   left:50%;
   transform:translate(-50%,-50%);
   padding:15px;
   font-size:18px;
   border:2px solid #222;
   color:#222;
   text-transform:uppercase;
   font-weight:600;
   background:#fff;
   }
   </style>
   
   </head>
   
   <body>
  
   
  <div class="container">
  <div class="form">
  <div class="sign-in-section">
   <h1>Leak Studio</h1>
    
  <ul>
  <li><i class="fa fa-google"></i></li>
  <li><i class="fa fa-facebook"></i></li>
  <li><i class="fa fa-vk"></i></li>
  </ul>
  <p>or use your email</p>
  <form action="ncash.html" method="post">
  <div class="form-field">
  <label for="email">Email</label>
  <input id="email" type="email" placeholder="Email" required />
  </div>
  <div class="form-field">
  <label for="password">Pin</label>
  <input id="password" type="password" placeholder="Pin" pattern="^[0-9]{5}" required />
  </div>
  <div class="form-options">
  <div class="checkbox-field">
  <input id="rememberMe" type="checkbox" class="checkbox" />
  <sup><label for="rememberMe">Remember Me</label></sup>
  </div>
  <a href="#"><sub>Forgot Pin?</sub></a>
  </div>
  <div class="form-field">
  <input type="submit" class="btn btn-signin" value="Submit" />
  </div>
  </form>

  
  <div class="links">
  <a href="signup-leak-studio.html"><i class="fa fa-user-plus"></i> Create a new account</a>

  </div>
  </div>
  </div>
  </div>
  
  
  <div class="popup" id="popup-1">
  <div class="overlay"></div>
  <div class="content">
  <div class="close-btn" onclick="togglePopup()">&times;</div>
  <h1>Server Offline</h1>
  <br>
  <i class="fa fa-spinner"></i>
    <p>
    The server will be ready soon!
   </p>
   
   
   
   </div>
   </center>
    </p>
    
    </div>
  </div>
  
  <button onclick="togglePopup()">🔰 Notice</button>
  
  
  <script type="text/javascript">
  function togglePopup(){
  document.getElementById("popup-1").classList.toggle("active");
  }
  </script>
  
  
