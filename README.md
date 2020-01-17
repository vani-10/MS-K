# MS-K
Working on HTML
Created a website on "How to prepare an egg omlette" using HTML CSS and javascript

#Code for HTML#

<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width">
    <title>repl.it</title>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css" type="text/css" />

    <link href="index.css" rel="stylesheet" type="text/css" />
  </head>
  <body>
    <div id="container">
     <header>
       <h1>How to make an Egg Omelet</h1>
        <img src ="https://i.imgur.com/yphXwOe.jpg">
        <p>
          Making an omelet can be easy within a short span of time. In just a few quick steps, learn how to make the best omelet with significant nutritional benefits that goes easy for any meal.
        </p>
    </header>
    <section id="ingredients" onmouseover="ingredientsHover()" onmouseout="ingredientsNormal()">
        <h2>Ingredients <i class="fa fa-cutlery" aria-hidden="true"></i>
</h2>
        <ul>
          <li>2	EGGS</li>
          <li>2	Tbsp. water</li>
          <li>1/8	tsp. salt</li>
          <li>Dash	pepper</li>
          <li>1	tsp. butter</li>
          <li>1/3 to 1/2	cup filling, such as shredded cheese, finely chopped ham, baby spinach (optional)</li>
        </ul>
    </section>
    <section id="preparation" onmouseover="preparationHover()" onmouseout="preparationNormal">
        <h2>Preparation <i class="fa fa-check" aria-hidden="true"></i>
</h2>
        <ol>
      <li>BEAT eggs, water, salt and pepper in small bowl until blended.</li>
      <li>HEAT butter in 7 to 10-inch nonstick omelet pan or skillet over medium-high heat until hot. TILT pan to coat bottom. POUR IN egg mixture. Mixture should set immediately at edges.</li>
      <li>GENTLY PUSH cooked portions from edges toward the center with inverted turner so that uncooked eggs can reach the hot pan surface. CONTINUE cooking, tilting pan and gently moving cooked portions as needed.</li>
      <li>When top surface of eggs is thickened and no visible liquid egg remains, PLACE filling on one side of the omelet. FOLD omelet in half with turner. With a quick flip of the wrist, turn pan and INVERT or SLIDE omelet onto plate. SERVE immediately.</li>
    </ol>
    </section>
    <footer>
        <p>Copyright Kavi 2020</p>
    </footer>
    </div>
    <script>
        function ingredientsHover() {
            document.getElementById('ingredients').firstElementChild.firstElementChild.style.fontSize = '300%';
        }


        function ingredientsNormal() {
            document.getElementById('ingredients').firstElementChild.firstElementChild.style.fontSize = '100%';
            // document.write("Normal");  
        }


        function preparationHover() {
            document.getElementById('preparation').firstElementChild.firstElementChild.style.fontSize = '300%';
        }


        function preparationNormal() {
            document.getElementById('preparation').firstElementChild.firstElementChild.style.fontSize = '100%';
        }
    </script>

    
  </body>
</html>#

#code for CSS#
body {
 font-family: Arial;
 color: SlateGrey;
}

#container {
 width: 60%;
 margin: auto;
}

h1 {
 font-size: 300%;
}

h2 {
 color: Green;
 text-transform: uppercase;
 font-weight: 100;
}

img {
 width: 100%;
}


footer {
 margin-top: 70px;
 background-color: Orange;
 color: White;
}

footer p {
 text-align: center;
 padding-top: 15px;
 padding-bottom: 15px;
}

@media screen and (max-width :768px)
{
#container {
 width: 90%;

}
h1
{
 font-size: 200%;
}

}

