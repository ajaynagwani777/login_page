# login_page with html and css
<!DOCTYPE html>
<html>
<head>
<style>
input[type=text],input[type=date],input[type=password] {
    border: 2px solid #330033;
    border-radius: 7px;
}
body {
    background-image: url("http://ipadinsight.com/wp-content/uploads/2013/02/Dark-Simple-Grungy-iPad-wallpaper.jpg");
    background-size: 2000px 1000px;
    background-repeat: no-repeat;

}
h3
{
 padding:5px;
  margin:0px;
}
input[type=button] {
    background-color: rgb(255,0,0);
    text-decoration: none;
    margin: 4px 2px;
    cursor: pointer;
}
.cancelbtn {
    margin-left:30px;
    width: auto;
    padding: 10px 25px;
    font-size:18px;
    border-radius: 5px;
}
span.psw {
    
    margin-left:350px;
    font-size:18px;
}
.container 
{
    padding: 16px;
}
.imgcontainer
{
    margin-top: 10px;
    margin-bottom: 10px;
    margin-right: 200px;
    margin-left: 200px;
 }
div.container1 
{
    height:700px;
    width :35%; 
    border: 0px solid black;
    margin-top: 100px;
    margin-bottom: 50px;
    margin-right: 50px;
    margin-left: 600px;
    background-color:rgba(255, 255, 255,0.1);
    border-radius: 20px;
 
}
div.container2 
{
    height:400px;
    width :50%; 
    border: 0px solid black;
    margin-top: 50px;
    margin-bottom: 0px;
    margin-right: 50px;
    margin-left: 140px;
    background-color: rgba(255, 255, 255, 0);

}
input
{
font-size:32px
}
.submitbtn 
{
    width: 130px;
    height: 40px;
    font-size: 22px;
    font-weight:bold;
    border-radius: 5px;
    
}

.checkbox
{
         font-size : 20px;
}
</style>

</head>

<body>
<div class= "container1" >
          <img src="http://www.appwallaz.com/img/logo.png" width="650px" height="170px" align="center" alt="logo"/>
          <form action="http:appwallaz.com">
              <div class="container2">
                   <h3>USERNAME:</h3>
                      <input type="text" placeholder=" Enter Username" name="uname"  required>
                      <br><br>
                  <h3>PASSWORD:</h3>
                      <input type="password" placeholder=" Enter password" name="password" required>
                     <br><br>
                 <h3>DATE OF BIRTH:</h3>
                     <input type="date" placeholder="Enter dob" name="dob" required>
                     <br><br><br>
                     <button type="submit" class="submitbtn" onclick="myFunction()">login</button>
                         <script>
                               function myFunction() 
                                   {
                                       if (window.confirm('You have been Logged In.\n Click OK to continue.')) 
                                           { 
                                                 window.location.href='https://www.appwallaz.com';
                                           } 
                                   }
                        </script>
                       <br><br>
                      <input type="checkbox" class="checkbox" checked="checked" >Remember me</input>
                      </div class="container">
                               <button type="button" class="cancelbtn">Cancel</button>
                                <span class="psw"><a href="#">forgot password?</a></span>
                      </div>
              </form>

</body>
</html>
