<template>
  <form action="/action_page.php">
    <div class="header">
      <img src="../download.png" alt="google logo">
      <p id="sign">Sign in</p>
      <p id="use">Use your Google Account</p>
    </div>
    <div id="box">
      <input type="text" placeholder="Email or phone">
    </div>
    <button id="forgot">Forgot email?</button>

    <p id="not">Not your computer? Use Guest mode to sign in privately.</p>
    <button id="learn">Learn more</button>

    <div class="button">
      <button id="create">Create account</button>
      <button id="next"><b>Next</b></button>
    </div>

  </form>
  <button class="btn">English (United Kingdom)</button>
  <div class="dropdown">
    <button class="btn">
      <i class="fa fa-caret-down"></i>
    </button>

    <div class="dropdown-content">
      <a href="#" class="language">English (United Kingdom)</a>
      <a href="#" class="language uk">Bahasa Melayu</a>
      <a href="#" class="language uk">Chinese Traditional</a>
      <a href="#" class="language uk">Chinese Simplified</a>
    </div>

  </div>
  <span id="help">Help</span>
  <span id="privacy">Privacy</span>
  <span id="term">Terms</span>
</template>

<script>

</script>

<style scoped>
body {
  font-family: Arial, Helvetica, sans-serif;
  margin: auto;
  width: 50%;
}

form {
  margin: auto;
  margin-top: 10%;
  height: 550px;
  width: 500px;
  border: 1.5px solid #ccc;
  border-radius: 10px;
}



img{
  margin-top: 5%;
  margin-left: 35%;
  width: 30%;
}

#sign{
  font-size: 25px;
  text-align: center;
  margin-top: -2%;

}

#use{
  font-size: 20px;
  text-align: center;
  margin-top: -3%;

}

input[type=text] {
  width: 400px;
  height: 50px;
  padding: 12px 20px;
  margin: 15px 0;
  margin-left: 43px;
  display: inline-block;
  border: 1px solid #ccc;
  box-sizing: border-box;
  border-radius: 5px;
}
input[type=text]:focus::placeholder,
input[type=text]:not(:placeholder-shown)::placeholder{
  font-size: 12px;
  position: absolute;
  top: 0;
  left: 0;
  transform: translate(5px, 5px);
  transition: all 0.2s ease-in-out;
  color: #2364f1;
}
input:focus{
  border-color: #2364f1;
}

#forgot{
  border: transparent;
  background-color: transparent;
  font-size: 15px;
  margin-top: -1%;
  margin-left: 8.5%;
  color: #2159f3;
}

#not{
  font-size: 15px;
  margin-left: 8.5%;
  margin-top: 10%;
  color: #03030389;

}

#learn{
  border: transparent;
  background-color: transparent;
  font-size: 15px;
  margin-left: 8.5%;
  margin-top: -3%;
  color: #2159f3;
}

.button{
  margin-left: 8.5%;
  margin-top: 10%;
}

#create{
  border: transparent;
  background-color: transparent;
  font-size: 16px;
  color: #2159f3;
}

#next{
  margin-left: 42%;
  background-color: #2196F3;;
  border: none;
  color: white;
  padding: 14px 28px;
  font-size: 18px;
  cursor: pointer;
  border-radius: 5px;

}

#next:hover{
  background: #0b7dda;
}

.btn {
  margin-left: 17%;
  background-color: transparent;
  color: black;
  padding: 16px 5px 16px 6px;
  font-size: 16px;
  border: none;
  outline: none;
}

.dropdown {
  position: absolute;
  display: inline-block;
}

.dropdown-content {
  display: none;
  position: absolute;
  background-color: #f1f1f1;
  min-width: 160px;
  z-index: 1;
}

.dropdown-content a {
  color: black;
  padding: 12px 16px;
  text-decoration: none;
  display: block;
  font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
}

.dropdown-content a:hover {background-color: #ddd}

.dropdown:hover .dropdown-content {
  display: block;
}

.fa-caret-down {
  color: black;
}

.btn:hover, .dropdown:hover .btn {
  background-color: transparent;
}

.dropdown:hover .fa-caret-down {
  transform: rotate(180deg);
}

.dropdown:hover .dropdown-content a.language {
  display: none;
}

.dropdown:hover .dropdown-content a.language.uk {
  display: block;
}

#help {
  font-size: 15px;
  display: inline-block;
  margin-left: 5px;
  vertical-align: middle;
  margin-left: 12%;
}

#privacy {
  font-size: 15px;
  display: inline-block;
  margin-left: 5px;
  vertical-align: middle;
  margin-left: 5%;
}

#term {
  font-size: 15px;
  display: inline-block;
  margin-left: 5px;
  vertical-align: middle;
  margin-left: 5%;
}
</style>