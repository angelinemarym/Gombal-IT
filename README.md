<html>
  <body>
    <h1>Hai Cantik!</h1>
    <img src="https://c.tenor.com/Z8ezUHZzcLoAAAAC/love.gif" />
    <h1>Maukah kamu menjadi pacarku?</h1>
    <button id="btn_mau" onclick="alert('I LOVE YOU')">Mau</button>&nbsp;
    <button id="btn_gamau" onclick="gamau(this)" style="position: absolute">
      Gamau
    </button>
  </body>
  <script>
    function gamau(id) {
      var mau = document.getElementById("btn_mau");
      var i = Math.floor(Math.random() * 300) + 1;
      var j = Math.floor(Math.random() * 100) + mau.offsetTop;
      id.style.left = i + "px";
      id.style.top = j + "px";
    }
  </script>
</html>
