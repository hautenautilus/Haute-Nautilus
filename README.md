# Haute-Nautilus
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Your Site</title>
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; }
    body {
      font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif;
      min-height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      background: linear-gradient(-45deg, #ee7752, #e73c7e, #23a6d5, #23d5ab);
      background-size: 400% 400%;
      animation: gradient 15s ease infinite;
    }
    @keyframes gradient {
      0% { background-position: 0% 50%; }
      50% { background-position: 100% 50%; }
      100% { background-position: 0% 50%; }
    }
    .container {
      text-align: center;
      padding: 2rem;
      background: rgba(255,255,255,0.95);
      border-radius: 20px;
      box-shadow: 0 20px 60px rgba(0,0,0,0.3);
      max-width: 500px;
      width: 90%;
    }
    h1 {
      font-size: 2.5rem;
      margin-bottom: 1rem;
      color: #333;
    }
    p {
      font-size: 1.2rem;
      margin-bottom: 2rem;
      color: #666;
    }
    .logo {
      width: 100px;
      height: 100px;
      background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
      border-radius: 50%;
      margin: 0 auto 2rem;
    }
    @media (prefers-reduced-motion: reduce) {
      body { animation: none; }
    }
  </style>
</head>
<body>
  <div class="container">
    <div class="logo"></div>
    <h1>Coming Soon</h1>
    <p>Drop your email to be the first to know when we launch!</p>
    <div id="custom-substack-embed"></div>
  </div>
  
  <script>
    window.CustomSubstackWidget = {
      substackUrl: "https://hautenautilus.substack.com/",
      placeholder: "Enter your email",
      buttonText: "Get Early Access",
      theme: "custom",
      colors: {
        primary: "#667eea",
        input: "#f5f5f5",
        email: "#333",
        text: "#fff"
      }
    };
  </script>
  <script src="https://substackapi.com/widget.js" async></script>
</body>
</html>

