<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Welcome to the Cool Site</title>
  <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@500&display=swap" rel="stylesheet">
  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
      font-family: 'Orbitron', sans-serif;
    }

    body {
      background: linear-gradient(to right, #0f2027, #203a43, #2c5364);
      color: white;
      height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
    }

    .container {
      text-align: center;
      max-width: 700px;
      padding: 2rem;
    }

    .question-box, .content {
      background: rgba(0,0,0,0.7);
      border-radius: 12px;
      padding: 2rem;
      box-shadow: 0 0 20px #0ff;
      transition: opacity 0.5s ease, transform 0.5s ease;
    }

    .question-box button {
      margin: 1rem;
      padding: 0.8rem 1.6rem;
      border: none;
      background: #00f2fe;
      color: black;
      border-radius: 8px;
      font-size: 1.1rem;
      cursor: pointer;
      transition: 0.3s ease;
    }

    .question-box button:hover {
      background: #4facfe;
    }

    .hidden {
      display: none;
    }

    .content img {
      width: 100%;
      border-radius: 12px;
      margin-top: 1rem;
    }

    h1, h2 {
      margin-bottom: 1rem;
    }

    p {
      line-height: 1.6;
      font-size: 1.1rem;
    }
  </style>
</head>
<body>

<div class="container">
  <div class="question-box" id="welcomeBox">
    <h1>Welcome Mr RIP RIP</h1>
    <h2>Are you a gay and want to kiss Margik?</h2>
    <button onclick="enterSite()">Yes</button>
    <button onclick="denyEntry()">No</button>
  </div>

  <div class="content hidden" id="mainContent">
    <h1>🎉 Iknew that you are a gay!!</h1>
    <p>if you dont stop being gay cauliflower will be out from your butt. so stop being gay. love from Margik</p>
    <img src="https://images.unsplash.com/photo-1567476783296-fff06012e17a?q=80&w=774&auto=format&fit=crop&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D" alt="Cool Nature">
    <p>love u ummaa</p>
  </div>
</div>

<script>
  function enterSite() {
    document.getElementById("welcomeBox").classList.add("hidden");
    document.getElementById("mainContent").classList.remove("hidden");
  }

  function denyEntry() {
    alert("Sorry! You need to identify as a gay to enter.");
  }
</script>

</body>
</html>
