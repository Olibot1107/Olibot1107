```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>Say Hi Button</title>
</head>
<body>

<button id="sayHiBtn">Click me!</button>

<script>
  document.getElementById('sayHiBtn').addEventListener('click', () => {
    alert('Hi!');
  });
</script>

</body>
</html>
