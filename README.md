<!-- html code -->
<!DOCTYPE html>
<html>
    <head>
        <meta name="generator" content="" />
        <meta name="viewport" content="width=device-width, initial-scale=1">
        <meta name="viewport" content="width=device-width, initial-scale=1">
        <title>Homepage</title>
        <link href="style.css" rel="stylesheet" type="text/css">
    </head>
    <body>
        <div class="Rectangle"></div>
        <div class="Square"></div>
        <div class="square2"></div>
    </body>
</html>

/* css code */
.Rectangle {
    position: absolute;
    height: 130px;
    width: 1364px;
    background-color: grey;
    margin-left: -8px;
    margin-top: -58px;
  }
.Square {
    width: 50px;
    height: 50px;
    background-color:orange;
    position: relative;
    margin-top: 15px;
    animation-name: TriangleType;
    animation-duration: 7s;
}
@keyframes TriangleType {
    10%   {background-color:black; left:0px; top:0px;}
    25%  {background-color:orange; left:200px; top:0px;}
    50%  {background-color:green; left:700px; top:0px;}
    75%  {background-color:lightblue; left:500px; top:0px;}
    100% {background-color:orange; left:0px; top:0px;}
  }

  .square2 {
    width: 50px;
    height: 50px;
    background-color:orange;
    position: relative;
    margin-top: 50px;
    animation-name: square2type;
    animation-duration: 8s;
}
@keyframes square2type {
    10%   {background-color:blue; left:0px; top:0px;}
    25%  {background-color:orange; left:200px; top:0px;}
    50%  {background-color:green; left:700px; top:0px;}
    75%  {background-color:lightblue; left:500px; top:0px;}
    100% {background-color:orange; left:0px; top:0px;}
  }
