<html>
  <body>
    <h2> ____ </h2>
    <p id="number"></p>
    <script>
      var text = "";
      var i = 0;
      while (i < 11) {
        text += "<br>The Random Number That Was Generated Is... " + i;
        i++;
      }
      document.getElementById("number").innerHTML = text;
    </script>
  </body>
</html>
