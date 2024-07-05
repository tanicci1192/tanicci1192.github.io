<!DOCTYPE html>
<html>
  <head>
      <title>OAuth Callback</title>
      <script>
          // URLのパラメータを取得
          const params = new URLSearchParams(window.location.search);
          const code = params.get('code');
          // OAuthコードを表示
          document.addEventListener('DOMContentLoaded', () => {
              document.getElementById('code').textContent = code;
          });
      </script>
  </head>
  
  <body>
      <h1>OAuth Callback</h1>
      <p>OAuthコード: <span id="code"></span></p>
  </body>
</html>
