# Project Responsive Web Design using Bootstrap
# Date:09.10.25
# AIM:
To create a simplified clone of Dribbble (https://dribbble.com/) landing page.

# DESIGN STEPS:
## Step 1:
Clone the repository from GitHub.

## Step 2:
Create Django Admin project.

## Step 3:
Create a New App under the Django Admin project.

## Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

## Step 5:
Create a HTML file and include the needed Bootstrap components.

## Step 6:
Publish the website in the LocalHost.

# PROGRAM :
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Home - Shopping World</title>
<style>
body {
  font-family: Arial, sans-serif;
  margin: 0;
  background-color: #f8f9fa;
}
nav {
  background-color: #222;
  overflow: hidden;
}
nav a {
  float: left;
  display: block;
  color: white;
  text-align: center;
  padding: 14px 20px;
  text-decoration: none;
}
nav a:hover {
  background-color: #f39c12;
}
.active {
  background-color: #f39c12;
}
.container {
  text-align: center;
  padding: 40px 20px;
}
.gallery {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 15px;
  margin-top: 20px;
}
.gallery img {
  width: 200px;
  height: 200px;
  border-radius: 10px;
  transition: 0.3s;
}
.gallery img:hover {
  transform: scale(1.05);
}
footer {
  background-color: #222;
  color: white;
  text-align: center;
  padding: 10px;
  margin-top: 40px;
}
</style>
</head>
<body>

<nav>
  <a class="active" href="home.html">Home</a>
  <a href="electronic.html">Electronics</a>
  <a href="fashion.html">Fashion</a>
  <a href="foot weare.html">Footwear</a>
  <a href="login.html" class="login">Login</a>

</nav>

<div class="container">
  <h1>Welcome to Shopping World!</h1>
  <p>Your one-stop shop for Electronics, Fashion & Footwear.</p>

  <div class="gallery">
    <img src="Screenshot 2025-10-14 235058.png" alt="Shop 1">
    <img src="Screenshot 2025-10-14 234939.png" alt="Shop 2">
    <img src="Screenshot 2025-10-14 234716.png" alt="Shop 3">
    <img src="Screenshot 2025-10-14 234816.png" alt="Shop 4">
    <img src="Screenshot 2025-10-15 065914.png" alt="Camera">
    <img src="Screenshot 2025-10-15 070111.png" alt="Camera">
  </div>
</div>

<footer>
  &copy; 2025 Shopping World | Designed by Ishwarya
</footer>

</body>
</html>

electronic.html
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Electronics - Shopping World</title>
<style>
body {
  font-family: Arial, sans-serif;
  margin: 0;
  background-color: #eef2f3;
}
nav {
  background-color: #222;
  overflow: hidden;
}
nav a {
  float: left;
  display: block;
  color: white;
  text-align: center;
  padding: 14px 20px;
  text-decoration: none;
}
nav a:hover {
  background-color: #3498db;
}
.active {
  background-color: #3498db;
}
.container {
  text-align: center;
  padding: 40px 20px;
}
.gallery {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 15px;
  margin-top: 20px;
}
.gallery img {
  width: 200px;
  height: 200px;
  border-radius: 10px;
  transition: 0.3s;
}
.gallery img:hover {
  transform: scale(1.05);
}
footer {
  background-color: #222;
  color: white;
  text-align: center;
  padding: 10px;
  margin-top: 40px;
}
</style>
</head>
<body>

<nav>
  <a href="index.html">Home</a>
  <a class="active" href="electronic.html">Electronics</a>
  <a href="fashion.html">Fashion</a>
  <a href="foot weare.html">Footwear</a>
  <a href="login.html" class="login">Login</a>

</nav>

<div class="container">
  <h2>Latest Electronics</h2>
  <p>Shop top brands for mobiles, laptops, and gadgets.</p>

  <div class="gallery">
    <img src="Screenshot 2025-10-15 002417.png" alt="Laptop">
    <img src="Screenshot 2025-10-15 002537.png" alt="bluetooth">
    <img src="Screenshot 2025-10-15 002747.png" alt="Mobile">
    <img src="Screenshot 2025-10-15 002851.png" alt="Camera">
    <img src="Screenshot 2025-10-15 065420.png" alt="Camera">
    <img src="Screenshot 2025-10-15 065504.png" alt="Camera">
    <img src="Screenshot 2025-10-15 065610.png" alt="Camera">
    <img src="Screenshot 2025-10-15 065710.png" alt="Camera">
  </div>
</div>

<footer>
  &copy; 2025 Shopping World | Designed by Ishwarya
</footer>

</body>
</html>

fasion.html
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Fashion - Shopping World</title>
<style>
body {
  font-family: Arial, sans-serif;
  margin: 0;
  background-color: #fff5f7;
}
nav {
  background-color: #222;
  overflow: hidden;
}
nav a {
  float: left;
  display: block;
  color: white;
  text-align: center;
  padding: 14px 20px;
  text-decoration: none;
}
nav a:hover {
  background-color: #e84393;
}
.active {
  background-color: #e84393;
}
.container {
  text-align: center;
  padding: 40px 20px;
}
.gallery {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 15px;
  margin-top: 20px;
}
.gallery img {
  width: 150px;
  height: 200px;
  border-radius: 10px;
  transition: 0.3s;
}
.gallery img:hover {
  transform: scale(1.05);
}
footer {
  background-color: #222;
  color: white;
  text-align: center;
  padding: 10px;
  margin-top: 40px;
}
</style>
</head>
<body>

<nav>
  <a href="index.html">Home</a>
  <a href="electronic.html">Electronics</a>
  <a class="active" href="fashion.html">Fashion</a>
  <a href="foot weare.html">Footwear</a>
  <a href="login.html" class="login">Login</a>

</nav>

<div class="container">
  <h2>Trendy Fashion Collection</h2>
  <p>Explore the latest clothing and accessories.</p>

  <div class="gallery">
    <img src="Screenshot 2025-10-15 062329.png" alt="t shirts">
  <img src="Screenshot 2025-10-15 062544.png" alt="traditional">
  <img src="Screenshot 2025-10-15 062822.png" alt="casual weare">
  <img src="Screenshot 2025-10-15 062940.png" alt="modern dressses">
  <img src="Screenshot 2025-10-15 063305.png" alt="party weare">
  <img src="Screenshot 2025-10-15 063410.png" alt="jeans">
  <img src="Screenshot 2025-10-15 063455.png" alt="ethinic weare">
  <img src="Screenshot 2025-10-15 063758.png" alt="Accessories">
  <img src="Screenshot 2025-10-15 063623.png" alt="watches">
  <img src="Screenshot 2025-10-15 060131.png" alt="Street Style">

    
  </div>
</div>

<footer>
  &copy; 2025 Shopping World | Designed by Ishwarya
</footer>

</body>
</html>
foot weare.html

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Footwear - Shopping World</title>
<style>
body {
  font-family: Arial, sans-serif;
  margin: 0;
  background-color: #f2f8ff;
}
nav {
  background-color: #222;
  overflow: hidden;
}
nav a {
  float: left;
  display: block;
  color: white;
  text-align: center;
  padding: 14px 20px;
  text-decoration: none;
}
nav a:hover {
  background-color: #2ecc71;
}
.active {
  background-color: #2ecc71;
}
.container {
  text-align: center;
  padding: 40px 20px;
}
.gallery {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 15px;
  margin-top: 20px;
}
.gallery img {
  width: 200px;
  height: 200px;
  border-radius: 10px;
  transition: 0.3s;
}
.gallery img:hover {
  transform: scale(1.05);
}
footer {
  background-color: #222;
  color: white;
  text-align: center;
  padding: 10px;
  margin-top: 40px;
}
</style>
</head>
<body>

<nav>
  <a href="index.html">Home</a>
  <a href="electronic.html">Electronics</a>
  <a href="fashion.html">Fashion</a>
  <a class="active" href="foot weare.html">Footwear</a>
  <a href="login.html" class="login">Login</a>

</nav>

<div class="container">
  <h2>Stylish Footwear</h2>
  <p>Find shoes, sandals, and sneakers that fit your style.</p>

  <div class="gallery">
    <img src="Screenshot 2025-10-15 000803.png" alt="Boots">
    <img src="Screenshot 2025-10-15 000843.png" alt="Sneakers">
    <img src="Screenshot 2025-10-15 000930.png" alt="Shoes">
    <img src="Screenshot 2025-10-15 001032.png" alt="Casual Shoes">
    <img src="Screenshot 2025-10-15 001748.png" alt="shoes">
    <img src="Screenshot 2025-10-15 064450.png" alt="shoes">
    <img src="Screenshot 2025-10-15 064646.png" alt="Accessories">
    <img src="Screenshot 2025-10-15 064730.png" alt="watches">
    <img src="Screenshot 2025-10-15 064823.png" alt="Street Style">
    

    
  </div>
</div>

<footer>
  &copy; 2025 Shopping World | Designed by Ishwarya
</footer>

</body>
</html>

login.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Login - Shopping World</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #fff5f7;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      margin: 0;
    }
    .login-box {
      background-color: #ffffff;
      padding: 40px;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
      width: 300px;
      text-align: right;
    }
    .login-box h2 {
      margin-bottom: 20px;
      color: #e84393;
    }
    .login-box input[type="text"],
    .login-box input[type="password"] {
      width: 100%;
      padding: 10px;
      margin: 10px 0;
      border: 1px solid #ccc;
      border-radius: 5px;
    }
    .login-box button {
      width: 100%;
      padding: 10px;
      background-color: #e84393;
      color: white;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }
    .login-box button:hover {
      background-color: #d63074;
    }
  </style>
</head>
<body>

  <div class="login-box">
    <h2>Login</h2>
    <form>
      <input type="text" placeholder="Username" required>
      <input type="password" placeholder="Password" required>
      <button type="submit">Login</button>
    </form>
  </div>

</body>
</html>


# OUTPUT:


![alt text](<Screenshot 2025-10-15 070752.png>)


![alt text](<Screenshot 2025-10-15 070812.png>)

![alt text](<Screenshot 2025-10-15 070826.png>)


![alt text](<Screenshot 2025-10-15 070839.png>)


![alt text](<Screenshot 2025-10-15 070857.png>)

# RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
