# WT-Fall
webtech project
/> index</
<!DOCTYPE html>
<html>
<head>
	<title>
		 Library Management System
	</title>
	<link rel="stylesheet" type="text/css" href="style.css">
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">

<style type="text/css">
	nav
	{
		float: right;
		word-spacing: 30px;
		padding: 20px;
	}
	nav li 
	{
		display: inline-block;
		line-height: 80px;
	}
</style>
</head>


<body>
	<div class="wrapper">
		<header>
		<div class="logo">
			
			<h1 style="color: white;"> LIBRARY MANAGEMENT SYSTEM</h1>
		</div>
			<nav>
				<ul>
					<li><a href="index.php">HOME</a></li>
					<li><a href="books.php">BOOKS</a></li>
					<li><a href="student_login.php">STUDENT-LOGIN</a></li>
					<li><a href="admin_login.php">ADMIN-LOGIN</a></li>
					<li><a href="feedback.php">FEEDBACK</a></li>
				</ul>
			</nav>
		</header>
		<section>
		<div class="sec_img">
			<br><br><br>
			<div class="box">
				<br><br><br><br>
				<h1 style="text-align: center; font-size: 35px;">Welcom to library</h1><br><br>
				<h1 style="text-align: center;font-size: 25px;">Opens at: 09:00 am </h1><br>
				<h1 style="text-align: center;font-size: 25px;">Closes at: 5.00 pm </h1><br>
			</div>
		</div>
		</section>
		<footer>
			<p style="color:white;  text-align: center; ">
				<br><br>
				Email: library@gmail.com <br>
				Mobile: +88017********
			</p>
		</footer>
	</div>
</body>

</html>


<!DOCTYPE html>
<html>
<head>

  <title>Student Login</title>
  <link rel="stylesheet" type="text/css" href="style.css">
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">

  /<student login/<
</head>
<body>
<header style="height: 90px;">
  
<div class="logo">
      <h1 style="color: white; font-size: 25px;word-spacing: 10px; line-height: 80px;margin-top: 20px;">LIBRARY MANAGEMENT SYSTEM</h1>
    </div>

      <nav>
        <ul>
          <li><a href="index.php">HOME</a></li>
          <li><a href="">BOOKS</a></li>
          <li><a href="student_login.php">STUDENT-LOGIN</a></li>
          <li><a href="">ADMIN_LOGIN</a></li>
          <li><a href="">FEEDBACK</a></li>
        </ul>
      </nav>
</header>
<section>
  <div class="log_img">
    <br> <br><br>
    <div class="box1">
        <h1 style="text-align: center; font-size: 35px;font-family: Lucida Console;">Library Management System</h1><br>
        <h1 style="text-align: center; font-size: 25px;">User Login Form</h1><br>
      <form name="login" action="" method="">
        <br><br>
        

        <div class="login">
          <table>
          <tr>
            <td>
              Name :
            </td>
            <td>

           <input type="text" name="username" placeholder="Username" required=""> 
         </td>
       </tr>
       <tr>
        <td>
          Password :
        </td>
        <td>

            <input type="password" name="password" placeholder="Password" required="">     
          </td>
        </tr>
        <tr>
          <td>
          <button>Login</button>
        </td>
      </tr>
    </table>

        </div>
      </form>
      <p style="color: white; padding-left: 15px;">
        <br><br>
        <a style="color:black;" href="">Forgot password?</a> &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp
        New to this website?<a style="color: black;" href="registration.html">Sign Up</a>
      </p>
    </div>
  </div>
</section>

</body>
</html>


<!DOCTYPE html>
<html>
<head>

  <title>Student Registration</title>
  <link rel="stylesheet" type="text/css" href="style.css">
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">

</registration </
  
</head>
<body>
<header style="height: 90px;">
  
<div class="logo">
      <h1 style="color: white; font-size: 25px;word-spacing: 10px; line-height: 80px;margin-top: 20px;">LIBRARY MANAGEMENT SYSTEM</h1>
    </div>

      <nav>
        <ul>
          <li><a href="index.php">HOME</a></li>
          <li><a href="">BOOKS</a></li>
          <li><a href="student_login.php">STUDENT-LOGIN</a></li>
          <li><a href="registration.html">REGISTRATION</a></li>
          <li><a href="">FEEDBACK</a></li>
        </ul>
      </nav>
</header>

<section>
  <div class="reg_img">

    <div class="box2">
        <h1 style="text-align: center; font-size: 35px;font-family: Lucida Console;">Library Management System</h1><br>
        <h1 style="text-align: center; font-size: 25px;">User Registration Form</h1><br>
      <form name="Registration" action="" method="">
        <br><br>
        <div class="login">
          <h1 style="text-align:left; font-size: 20px;">
            <table>
          <tr>

              <td>  
                     Name:
              </td> 
                   <td>
                        <input type="text"  placeholder="First Name" required=""> 
                   </tr>
            </td>
   
               <tr>
          <td>

                         Last name: 
                 </td>
             <td>

              <input type="text"  placeholder="Last Name" required=""> 
              </tr>

              </td>           
                        <tr>
                          <td>
                            Username:

                          </td>
                          <td>

                            <input type="text"placeholder="Username" required=""> 
                          </td>
                        </tr>
          
                       <tr>
                  <td>
                Father's name: 
              </td>
              <td>

                        <input type="text" placeholder="Father's name" required=""> 

              </td>
          </tr>
          <tr>
            <td>
              Mother's name:
            </td>
            <td>

               <input type="text" placeholder="Mother's name" required=""> 
             </td>
           </tr>

                          <tr>
                 <td>
                            Gender :
               </td>
                    <td>
                        <input type = "radio" name="Gender"> Male
                         <input type = "radio" name="Gender"> Female
                 </td>
              </tr>

              <tr>
                <td>
                  Enter Id:

                </td>

                <td>
                  <input type="text"  placeholder="Id number" required="">
                </td>
              </tr>
              <tr>
                <td>
                  Depertment: 
                </td>
                <td>

          <input type="text" placeholder="Depertment" required="">
        </td>
      </tr>
           <tr>
            <td>
              Depertment :
            </td>
            <td>
              <input type = "radio" name=""> CSE
              <input type = "radio" name=""> BBA
              <input type = "radio" name=""> EEE
              <input type = "radio" name=""> LAW
            </td>
          </tr>

          <tr>
            <td>
              <br><br>Passportsize Photo:
            </td>
            <td>

              <form  placeholder="Choose photo"  required="">
         <input type="File"accept=".jpg">
         </form>
       </td>
     </tr>
     <tr>
      <td>
        Email:
      </td>
      <td>


           <input type="text"  placeholder="Email" required="">
         </td>
       </tr>
       <tr>
        <td>
          New Password:
        </td>
        <td>
           <input type="password" placeholder="Password" required=""> 
         </td>
       </tr>
       <tr>
        <td>
         Confirm password:
       </td>
       <td>


          <input type="password" placeholder="Confirm Password" required=""> 
        </td>
      </tr>
      <tr>
        <td>

          <button>Sign Up</button>
        </td>
      </tr>
        </div>
         </table>

       
      </form>
     
    </div>
  </div>
</section>
</body>
