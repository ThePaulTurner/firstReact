<!doctype html>

<html lang="en">


<head>
  <meta charset="utf-8">
  <title>React! React! React!</title>
  <script src="https://unpkg.com/react@16/umd/react.development.js"></script>
  <script src="https://unpkg.com/react-dom@16/umd/react-dom.development.js"></script>
  <script src="https://unpkg.com/babel-standalone@6.15.0/babel.min.js"></script>
  <style>
    #container {
    padding: 50px;
    background-color: #EEE;
}
    #container h1{
    font-size: 144px;
    font-family:sans-serif;
    color: #0080A8;
}
</style>

</head>

<body>
  <div id="container"></div>
  <script type="text/babel">
  var destination = document.querySelector("#container");

    ReactDOM.render 
    { 
        <h1>Paul Turner</h1>,
        destination
    };
  </script>
  
</body>
</html>
