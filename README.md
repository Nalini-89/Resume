<!DOCTYPE html>
<html>
<head>
  <title>Happy Birthday Nalini!</title>
  <style>
    body {
      font-family: sans-serif;
      text-align: center;
      background-color: #f0f0f0;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      margin: 0;
    }
    #birthdayMessage {
      background-color: white;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.2);
    }
    button {
      padding: 10px 20px;
      background-color: #4CAF50;
      color: white;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }
  </style>
</head>
<body>
  <div id="birthdayMessage">
    <h1>Happy Birthday Nalini!</h1>
    <p id="Nalini"></p>
    <button onclick="showName()">Enter Name</button>
  </div>

  <script>
    function showName() {
      const name = prompt("Nalini:");
      if (name != null && name != "") {
        document.getElementById("nameDisplay").innerText = "Wishing you a wonderful day, " + name + "!";
      }
    }
  </script>
</body>
</html>
            
        
