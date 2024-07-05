<html>
  <head>
    <title>iijmio</title>
    <style>
      .output {
        color: #333 ;
        text-align: center ;
        padding: 8px 0 ;
        border: 1px solid #333 ;
        min-height: 24px ;
      }
    </style>
  </head>

  <body>
    <p id="output" class="output"></p>
    <script>
      var resultElement = document.getElementById( "output" ) ;
      resultElement.innerHTML = location.hash ;
    </script>
  </body>
</html>
