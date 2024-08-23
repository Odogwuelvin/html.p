# html.p
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <title>CSS Flag Project</title>
  <style>
    .flag{
     background-color:red;
     width:900px;
     height:600px;
     position:relative;
     
    }
    .flag >p {
      color:white;
      font-size : 5rem;
      text-align:center;

    }
    .flag >div{
      background-color:blue;
      width:900px;
      height:300px;
      position:absolute;
      top:150px;
    }
    .flag >div div{
      background-color:white;
      border:2px solid white;
      width:200px;
      height:200px;
      border-radius :50%;
      position:absolute;
      top:50px;
      left:350px;
      text-align:center;
      color:black;
      font-size:4rem;

      


    }
    
  </style>
</head>

<!-- 
  IMPORTANT! Do not change any HTML
Don't add any classes/ids/elements 
Use what you know about combining selectors 
and CSS specificity instead.
Hint 1: The flag is 900px by 600px and the circle is 200px by 200px.
Hint 2: You can use CSS inspection to get the colors from
https://appbrewery.github.io/flag-of-laos/
-->

<body>
  <div class="flag">
    <p>The Flag</p>
    <div>
      <div>
        <p>of Laos</p>
      </div>
    </div>
  </div>
</body>

</html>
