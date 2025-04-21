# feb-2025-avasjcript-events-and-basic-interactivity
<!DOCTYPE html>
<html>
<head>
  <title>Button Click Example</title>
</head>
<body>

  <h2 id="text">Hello, world!</h2>
  <button onclick="changeText()">Click Me</button>

  <script>
    function changeText() {
      document.getElementById("text").innerText = "You clicked the button!";
    }
  </script>

</body>
</html>
