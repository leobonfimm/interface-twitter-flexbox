~~~html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Curso de FlexBox</title>

  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <div id="app">
    <div class="box red"></div>
    <div class="box green"></div>
    <div class="box blue"></div>
  </div>
</body>
</html>
~~~

~~~css
html, body, #app {
  height: 100%;
  margin: 0;
}

/* #app {
  display: flex;
  flex-direction: column;
  
  Alinha os intens da forma contraria do flex-direction
  align-items: center;

  Alinha os intens na mesma direção do flex-direction
  justify-content: space-around;
} */

#app {
  display: flex;
}


.box {
  width: 200px;
  height: 60px;
  background: #f00;
  margin: 5px;
}

.red {
  order: 3;
}

.green {
  background: #0f0;
  order: 2;
}

.blue {
  background: #00f;
  order: 0;
}
~~~