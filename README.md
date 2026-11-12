<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>User Registration</title>
  <style>
    * {
      box-sizing: border-box;
      font-family: Arial, sans-serif;
    }
    body {
      background-color: #f4f7f6;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      margin: 0;
    }
    .container {
      background-color: #ffffff;
      padding: 30px;
      border-radius: 8px;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
      width: 100%;
      max-width: 400px;
    }
    h2 {
      margin-top: 0;
      text-align: center;
      color: #333;
    }
    .form-group {
      margin-bottom: 15px;
    }
    label {
      display: block;
      margin-bottom: 5px;
      color: #555;
      font-weight: bold;
    }
    input {
      width: 100%;
      padding: 10px;
      border: 1px solid #ccc;
      border-radius: 4px;
      font-size: 14px;
    }
    button {
      width: 100%;
      padding: 12px;
      background-color: #28a745;
      border: none;
      border-radius: 4px;
      color: white;
      font-size: 16px;
      cursor: pointer;
    }
    button:hover {
      background-color: #218838;
    }
  </style>
</head>
<body>

  <div class="container">
    <h2>Create an Account</h2>
    <form action="#" method="POST">
      <div class="form-group">
        <label for="fullname">Full Name</label>
        <input type="text" id="fullname" name="fullname" required placeholder="Enter your full name">
      </div>
      <div class="form-group">
        <label for="email">Email Address</label>
        <input type="email" id="email" name="email" required placeholder="Enter your email">
      </div>
      <div class="form-group">
        <label for="password">Password</label>
        <input type="password" id="password" name="password" required placeholder="Create a password">
      </div>
      <div class="form-group">
        <label for="confirm-password">Confirm Password</label>
        <input type="password" id="confirm-password" name="confirm-password" required placeholder="Confirm your password">
      </div>
      <button type="submit">Register</button>
    </form>
  </div>

</body>
</html>
