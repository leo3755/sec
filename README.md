Ex.no.: 1                                 Resume Creation
Date :9/12/2025 
 
 Aim : 
               To create a resume using html and css.

Source code:  
Exp1.html
          <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Profile</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f8ff;
            text-align: center;
            color: #333; }
                  h1 {
            color: #4a90e2;
            margin-top: 20px; 
              }
                 img {
            width: 150px;
            height: auto;
            border-radius: 10px;
            border: 2px solid #ccc;
        }

        .profile-links a {
            display: block;
            color: #0078d4;
            font-size: 18px;
            font-weight: bold;
            margin: 10px auto;
            padding: 8px 15px;
            border-radius: 5px;
            width: 200px;
            text-decoration: none;
            border: 2px solid #0078d4;
            transition: 0.3s;
        }

        .profile-links a:hover {
            background-color: #0078d4;
            color: #fff;
        }

        .next-link {
            display: inline-block;
            margin-top: 20px;
            padding: 10px 20px;
            background-color: #4a90e2;
            color: #fff;
            border-radius: 5px;
            text-decoration: none;
            transition: 0.3s;
        }

        .next-link:hover {
            background-color: #3b72b2;
        }
    </style>
</head>
<body>
    <h1>My Profile</h1>
    <img src="student.jpg" alt="Profile Picture">

    <div class="profile-links">
        <a href="personal.html">Personal Profile</a>
        <a href="education.html">Education Profile</a>
        <a href="technical.html">Technical Profile</a>
    </div>

    <a class="next-link" href="personal.html">Next &rarr;</a>
</body>
</html>

Personal.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Personal Profile</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f8ff;
            text-align: center;
            color: #333;
        }

        h1 {
            color: #4a90e2;
            margin-top: 20px;
        }

        .profile-container {
            display: flex;
            justify-content: center;
            align-items: center;
            gap: 20px; /* Space between image and details */
            margin-top: 20px;
        }

        img {
            width: 150px;
            height: auto;
            border-radius: 10px;
            border: 2px solid #ccc;
        }

        .profile-details {
            font-size: 18px;
            background: #fff;
            padding: 15px;
            border-radius: 8px;
            box-shadow: 0 2px 6px rgba(0, 0, 0, 0.1);
            text-align: left;
            width: 250px;
        }

        .nav-wrapper {
            margin-top: 20px;
        }

        .nav-wrapper a {
            display: inline-block;
            text-decoration: none;
            font-size: 16px;
            font-weight: bold;
            padding: 10px 20px;
            border-radius: 5px;
            color: #fff;
            transition: 0.3s;
            margin: 5px;
        }

        .prev-link {
            background-color: #f76c6c;
        }

        .prev-link:hover {
            background-color: #d15555;
        }

        .next-link {
            background-color: #4a90e2;
        }

        .next-link:hover {
            background-color: #3b72b2;
        }
    </style>
</head>
<body>
    <h1>Personal Profile</h1>

    <div class="profile-container">
        <img src="student.jpg" alt="Profile Picture">
        <div class="profile-details">
            <p><strong>Name:</strong> Raj.S</p>
            <p><strong>Father's Name:</strong> xyz</p>
            <p><strong>DOB:</strong> 10/08/2005</p>
        </div>
    </div>

    <div class="nav-wrapper">
        <a href="exp1.html" class="prev-link">&larr; Previous</a>
        <a href="education.html" class="next-link">Next &rarr;</a>
    </div>
</body>
</html>
Education.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Education Profile</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f8ff;
            text-align: center;
            color: #333;
        }

        h1 {
            color: #4a90e2;
            margin-top: 20px;
        }

        .profile-container {
            display: flex;
            justify-content: center;
            align-items: center;
            gap: 20px; /* Space between image and details */
            margin-top: 20px;
        }

        img {
            width: 150px;
            height: auto;
            border-radius: 10px;
            border: 2px solid #ccc;
        }

        .profile-details {
            font-size: 18px;
            background: #fff;
            padding: 15px;
            border-radius: 8px;
            box-shadow: 0 2px 6px rgba(0, 0, 0, 0.1);
            text-align: left;
            width: 250px;
        }

        .nav-wrapper {
            margin-top: 20px;
        }

        .nav-wrapper a {
            display: inline-block;
            text-decoration: none;
            font-size: 16px;
            font-weight: bold;
            padding: 10px 20px;
            border-radius: 5px;
            color: #fff;
            transition: 0.3s;
            margin: 5px;
        }

        .prev-link {
            background-color: #f76c6c;
        }

        .prev-link:hover {
            background-color: #d15555;
        }

        .next-link {
            background-color: #4a90e2;
        }

        .next-link:hover {
            background-color: #3b72b2;
        }
    </style>
</head>
<body>
    <h1>Education Profile</h1>

    <div class="profile-container">
        <img src="student.jpg" alt="Profile Picture">
        <div class="profile-details">
            <p><strong>Qualification:</strong> abc</p>
            <p><strong>Degree:</strong> CS</p>
            <p><strong>Language:</strong> English, Tamil</p>
        </div>
    </div>

    <div class="nav-wrapper">
        <a href="personal.html" class="prev-link">&larr; Previous</a>
        <a href="technical.html" class="next-link">Next &rarr;</a>
    </div>
</body>
</html>
Technical.html
 <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Technical Profile</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f8ff;
            text-align: center;
            color: #333;
        }

        h1 {
            color: #4a90e2;
            margin-top: 20px;
        }

        .profile-container {
            display: flex;
            justify-content: center;
            align-items: center;
            gap: 20px; /* Space between image and details */
            margin-top: 20px;
        }

        img {
            width: 150px;
            height: auto;
            border-radius: 10px;
            border: 2px solid #ccc;
        }

        .profile-details {
            font-size: 18px;
            background: #fff;
            padding: 15px;
            border-radius: 8px;
            box-shadow: 0 2px 6px rgba(0, 0, 0, 0.1);
            text-align: left;
            width: 250px;
        }

        .nav-wrapper {
            margin-top: 20px;
        }

        .nav-wrapper a {
            display: inline-block;
            text-decoration: none;
            font-size: 16px;
            font-weight: bold;
            padding: 10px 20px;
            border-radius: 5px;
            color: #fff;
            transition: 0.3s;
            margin: 5px;
        }

        .prev-link {
            background-color: #f76c6c;
        }

        .prev-link:hover {
            background-color: #d15555;
        }

        .next-link {
            background-color: #4a90e2;
        }

        .next-link:hover {
            background-color: #3b72b2;
        }
    </style>
</head>
<body>
    <h1>Technical Profile</h1>

    <div class="profile-container">
        <img src="student.jpg" alt="Profile Picture">
        <div class="profile-details">
            <p><strong>Language:</strong> C, C++</p>
            <p><strong>Skill:</strong> Good communication</p>
            <p><strong>Additional:</strong> Leadership quality</p>
        </div>
    </div>

    <div class="nav-wrapper">
        <a href="education.html" class="prev-link">&larr; Previous</a>
        <a href="exp1.html" class="next-link">Next &rarr;</a>
    </div>
</body>
</html>

OUTPUT:
         























RESULT:
               Thus the above programme has been executed successfully.








	


Ex.no.: 2                                 Validation Form
Date :9/12/2025 

Aim : 
               To create a validation form using html and css.

Source code:  

        <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Login Form</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f8ff;
            text-align: center;
            margin: 0;
            padding: 0;
        }

        .login-container {
            width: 300px;
            margin: 100px auto;
            background: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
        }

        h2 {
            color: #4a90e2;
        }

        input {
            width: 90%;
            padding: 8px;
            margin: 10px 0;
            border: 1px solid #ccc;
            border-radius: 5px;
        }

        button {
            width: 100%;
            padding: 10px;
            background-color: #4a90e2;


           
           color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }

        button:hover {
            background-color: #3b72b2;
        }

        #message {
            margin-top: 10px;
            font-weight: bold;
        }
    </style>
</head>
<body>

    <div class="login-container">
        <h2>Login</h2>
        <input type="text" id="username" placeholder="Enter Username">
        <input type="password" id="password" placeholder="Enter Password">
        <button onclick="validateLogin()">Login</button>
        <p id="message"></p>
    </div>

    <script>
        function validateLogin() {
            var message = document.getElementById("message");

            if (document.getElementById("username").value === "admin" && 
                document.getElementById("password").value === "1234") {
                message.style.color = "green";
                message.innerText = "Login Successful!";
            } else {
                message.style.color = "red";
                message.innerText = "Login Failed!";
            }
        }
    </script>

</body>
</html>







   OUTPUT:























     RESULT:
                       Thus the above programme has been executed successfully.


	

Ex.no.: 3                                 Website Creation
Date :9/12/2025 

Aim : 
               To create a website using html and css.

Source code:  
Index.html
 <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Home</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <img src="logo.png" alt="Logo" class="logo">
        <nav>
            <a href="index.html">Home</a>
            <a href="about.html">About Us</a>
            <a href="contact.html">Contact Us</a>
            <a href="login.html">Login</a>
        </nav>
    </header>

    <div class="container">
        <h1>Welcome to Our Website</h1>
        <p>Discover amazing content and connect with us.</p>
    </div>
</body>
</html>
        About.html
            <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About Us</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <img src="logo.png" alt="Logo" class="logo">
        <nav>
            <a href="index.html">Home</a>
            <a href="about.html">About Us</a>
            <a href="contact.html">Contact Us</a>
            <a href="login.html">Login</a>
        </nav>
    </header>

    <div class="container">
        <h1>About Us</h1>
        <p>We are a passionate team dedicated to providing the best experience for our users.</p>
    </div>
</body>
</html>
       Contact.html
               <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <img src="logo.png" alt="Logo" class="logo">
        <nav>
            <a href="index.html">Home</a>
            <a href="about.html">About Us</a>
            <a href="contact.html">Contact Us</a>
            <a href="login.html">Login</a>
        </nav>
    </header>

    <div class="container">
        <h1>Contact Us</h1>
        <p>Email: support@example.com</p>
        <p>Phone: +123 456 7890</p>
    </div>
</body>
</html>
    Login.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Login</title>
    <link rel="stylesheet" href="style.css">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }

        body {
            background: url('background.jpg') no-repeat center center/cover;
            text-align: center;
            color: white;
        }

                header {
            display: flex;
            align-items: center;
            background: rgba(0, 0, 0, 0.8);
            padding: 15px 30px;
        }

        .logo {
            width: 50px;
            height: 50px;
        }

        nav {
            margin-left: auto;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 0 20px;
            font-weight: bold;
            font-size: 18px;
            transition: 0.3s ease;
        }

        nav a:hover {
            color: yellow;
            text-decoration: underline;
        }

               .login-container {
            width: 350px;
            margin: 120px auto;
            background:white;
            padding: 30px;
            border-radius: 10px;
            color: black;
            box-shadow: 0px 0px 12px rgba(0, 0, 0, 0.3);
        }

        input {
            width: 100%;
            padding: 12px;
            margin: 10px 0;
            border: 1px solid #ccc;
            border-radius: 6px;
            font-size: 16px;
        }

        button {
            width: 100%;
            padding: 14px;
            background-color: #4a90e2;
            color: white;
            border: none;
            border-radius: 6px;
            cursor: pointer;
            font-size: 16px;
            transition: 0.3s ease;
        }

        button:hover {
            background-color: #3b72b2;
        }

        /* Success Message */
        .success-message {
            display: none;
            color: green;
            font-weight: bold;
            margin-top: 15px;
            font-size: 16px;
        }
    </style>
</head>
<body>

    <header>
        <img src="logo.png" alt="Logo" class="logo">
        <nav>
            <a href="index.html">Home</a>
            <a href="about.html">About Us</a>
            <a href="contact.html">Contact Us</a>
            <a href="login.html">Login</a>
        </nav>
    </header>

    <div class="login-container">
        <h2>Login</h2>
        <form onsubmit="showSuccessMessage(event)">
            <input type="text" id="username" placeholder="Enter Username" required>
            <input type="password" id="password" placeholder="Enter Password" required>
            <button type="submit">Login</button>
            <p class="success-message" id="success-message">✅ Login Successful!</p>
        </form>
    </div>

    <script>
        function showSuccessMessage(event) {
            event.preventDefault();
            document.getElementById("success-message").style.display = "block";
        }
    </script>

</body>
</html>
     Style.css
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Arial, sans-serif;
}
body {
    background: url('background.jpg') no-repeat center center fixed;
    background-size: cover;
    height: 100vh;  /* Ensures it covers the full viewport height */
    width: 100vw;   /* Ensures it covers the full viewport width */
    color: white;
    text-align: center;
}
header {
    display: flex;
    align-items: center;
    background: rgba(0, 0, 0, 0.7);
    padding: 10px 20px;
}
.logo {
    width: 50px;
    height: 50px;
}
nav {
    margin-left: auto;
}
nav a {
    color: white;
    text-decoration: none;
    margin: 0 15px;
    font-weight: bold;
}nav a:hover {
    color: yellow;
}.container {
    margin-top: 100px;}

h1 {
    font-size: 36px;
    margin-bottom: 10px;
}p {
    font-size: 18px;
}

 OUTPUT:


	

   RESULT:
                 Thus the above programme has been executed successfully.
