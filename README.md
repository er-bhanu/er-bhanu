## Hi there 👋

<!--
**er-bhanu/er-bhanu** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Interactive GitHub Page</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      text-align: center;
      padding: 20px;
    }
    .button {
      padding: 10px 20px;
      font-size: 16px;
      cursor: pointer;
      margin: 10px;
      border: none;
      background-color: #28a745;
      color: white;
      border-radius: 5px;
    }
    .button:hover {
      background-color: #218838;
    }
    #output {
      margin-top: 20px;
      font-size: 18px;
      color: #333;
    }
  </style>
</head>
<body>
  <h1>Welcome to My Interactive GitHub Page</h1>
  <button class="button" onclick="displayMessage()">Click Me!</button>
  <div id="output"></div>

  <script>
    function displayMessage() {
      const outputDiv = document.getElementById('output');
      outputDiv.textContent = 'Hello, GitHub user! You clicked the button!';
    }
  </script>
</body>
</html>
