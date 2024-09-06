index.html

<!DOCTYPE html>
<html lang="PT-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>carros</title>
<link rel="stylesheet" href="css/index.css">

</head>
<body>
    
<center>
<img src="dvdd.png" alt=""  class="div">
</center>








</body>
</html>




index.css

body{

background-color: rgb(0, 0, 0);

}





.div{
  
  width: 100px;
  height: 100px;
  background: red;
  transition: width 2s;


}





.div:hover {
    width: 300px;
  }


  .div {
    transition: width 2s, height 4s;
  }
  



  /* The animation code */
@keyframes example {
  from {background-color: red;}
  to {background-color: yellow;}
}

/* The element to apply the animation to */
.div {
  width: 100px;
  height: 100px;
  background-color: red;
  border-radius: 50%;
  animation-name: example;
  animation-duration: 4s;
  padding: 10px ;

}

/* The animation code */
@keyframes example {
  0%   {background-color: red;}
  25%  {background-color: yellow;}
  50%  {background-color: blue;}
  100% {background-color: green;}
}

/* The element to apply the animation to */
.div {
  width: 100px;
  height: 100px;
  background-color: red;
  animation: example 4s infinite;

}



/* The animation code */
@keyframes example {
  0%   {background-color:red; left:0px; top:0px;}
  25%  {background-color:yellow; left:200px; top:0px;}
  50%  {background-color:blue; left:200px; top:200px;}
  75%  {background-color:green; left:0px; top:200px;}
  100% {background-color:red; left:0px; top:0px;}
}

/* The element to apply the animation to */
.div {
  width: 100px;
  height: 100px;
  position: relative;
  background-color: red;
  animation-name: example;
  animation-duration: 5s;
}
