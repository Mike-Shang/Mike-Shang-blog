# Mike-Shang-blog
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Cool HTML Page</title>
<style>
  body {
    margin: 0;
    padding: 0;
    background-color: #f0f0f0;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
  }
  .cool-text {
    font-size: 40px;
    font-family: 'Arial', sans-serif;
    text-align: center;
    color: #333;
    animation: color-change 5s infinite;
  }
  @keyframes color-change {
    0% { color: red; }
    25% { color: yellow; }
    50% { color: green; }
    75% { color: blue; }
    100% { color: red; }
  }
</style>
</head>
<body>
<div class="cool-text">Welcome to the Cool HTML Page!</div>
</body>
</html>
