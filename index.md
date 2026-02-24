---
layout: null
---
<html>
<head>
  <meta charset="UTF-8" />
  <meta http-equiv="refresh" content="3;url=https://jin0316.github.io/hyundong-jin/" />
  <title>Hyundong Jin</title>
  <style>
    body { font-family: Georgia, serif; display: flex; align-items: center; justify-content: center; min-height: 100vh; margin: 0; background: #fff; text-align: center; }
    h1 { font-size: 1.6rem; color: #18181b; margin-bottom: 1rem; }
    p { color: #71717a; line-height: 1.7; margin-bottom: 1rem; }
    a { color: #2563eb; font-weight: 600; }
  </style>
</head>
<body>
  <div>
    <h1>🎉 This page has been renewed!</h1>
    <p>Redirecting to my new homepage in <strong id="s">3</strong> seconds...</p>
    <p><a href="https://jin0316.github.io/hyundong-jin/">Click here if not redirected</a></p>
  </div>
  <script>
    let n=3; const el=document.getElementById('s');
    const t=setInterval(()=>{ n--; el.textContent=n; if(n<=0){ clearInterval(t); location.href='https://jin0316.github.io/hyundong-jin/'; }},1000);
  </script>
</body>
</html>
