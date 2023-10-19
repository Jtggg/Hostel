<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Hostel Management System</title>
  <link rel="stylesheet" href="styles.css">
</head>

<style>
  /* Your existing CSS styles go here */

  /* Add this code to set the background image */
  body {
    background-image: url("https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSTNQ6q3OAkgztd5p1VKkOo8SncqhUr5iz0qg&usqp=CAU");
    background-size: cover;
    background-repeat: no-repeat;
    background-position: center;
  }
  
  /* Additional styles for the login page */
  main {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 80vh;
  }
  
  .login-container {
    background-color: #f8f8f8;
    padding: 20px;
    border-radius: 5px;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
    text-align: center;
  }
  
  .login-container h2 {
    margin-bottom: 20px;
  }
  
  .login-container label {
    display: block;
    margin-bottom: 10px;
  }
  
  .login-container input {
    width: 100%;
    padding: 10px;
    margin-bottom: 20px;
    border: 1px solid #ccc;
    border-radius: 5px;
  }
  
  .login-container button {
    padding: 10px 20px;
    background-color: #007bff;
    color: #fff;
    border: none;
    border-radius: 5px;
    cursor: pointer;
  }
  
  .login-container button:hover {
    background-color: #0056b3;
  }
</style>
<body>
  
  <header>
    <h1>Welcome to the Royal Hostel</h1>
    <nav>
      <ul>
        <li class="dropdown-trigger"><a href="#">Home</a>
          <ul class="dropdown">
            <li><a href="#">About Us</a></li>
            <li><a href="#">Facilities</a></li>
            <li><a href="#">Gallery</a></li>
          </ul>
        </li>
        <li><a href="#">Rooms</a></li>
        <li><a href="#">Bookings</a></li>
        <li><a href="#">Contact</a></li>
      </ul>
    </nav>
  </header>

  <main>
    <div class="login-container">
      <h2>Login</h2>
      <form id="login-form">
        <label for="vtu-number">VTU Number:</label>
        <input type="text" id="vtu-number" name="vtu-number" required>
        <button type="submit">Login</button>
      </form>
    </div>
  </main>

  <footer>
    <p>&copy; 2023 Royal Hostel Management. All rights reserved.</p>
  </footer>

  <script src="script.js"></script>
</body>
</html>
