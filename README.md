<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Login Page</title>

  <style>
    body {
      margin: 0;
      font-family: Arial;
      height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      background: linear-gradient(to right, #4facfe, #00f2fe);
    }

    .box {
      background: white;
      padding: 30px;
      width: 300px;
      border-radius: 10px;
      box-shadow: 0 0 15px rgba(0,0,0,0.2);
      text-align: center;
    }

    input {
      width: 90%;
      padding: 10px;
      margin: 10px 0;
      border: 1px solid #ccc;
      border-radius: 8px;
    }

    button {
      width: 100%;
      padding: 10px;
      background: #4facfe;
      color: white;
      border: none;
      border-radius: 8px;
      cursor: pointer;
    }

    button:hover {
      background: #007bff;
    }
  </style>
</head>

<body>

  <div class="box">
    <h2>Login</h2>

    <input type="text" placeholder="Username">
    <input type="password" placeholder="Password">

    <button>Login</button>
  </div>

</body>
</html>