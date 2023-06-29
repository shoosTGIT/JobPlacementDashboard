# Live Project

## Introduction
For the last two weeks of my time at the tech academy, I worked with my peers in a team developing a few different sites in order to achieve a grander, more diverse webpage in HTML, CSS, and JavaScript. Working on a legacy codebase was a great learning oppertunity for fixing bugs, cleaning up code, and adding requested features. There were some big changes that could have been a large time sink, but we used what we had to deliver what was needed on time. I saw how a good developer works with what they have to make a quality product. I worked on [front end stories](#front-end-stories) that I'm quite fond of. Because much of the site had already been built, but not styled. I had to work and develop [front end styling](#front-end-styling) that had me stumped for a little bit. But like all the code stories provided and all of varying degrees of difficulty, nothing a little reset and different perspective to get the coding juices flowing. Everyone on the team had their own work and experiance to bring to the table, which really helped open up our code discussions at the end of the week.

##Front End Stories
* [Developing Travel Site](#Developing-travel-site)
* [Developing Recipe Site](#Developing-recipe-site)
* [Front End Styling](#front-end-styling)


### Developing Travel Site
So this site has a logo in the top left of the site, a nav element within the center ready to be linked to other sections of the site when ready. My tasks where to construct the whole site, front end and styling included.

<!--
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="utf-8">
  <title>Escap-e</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet" 
  integrity="sha384-9ndCyUaIbzAi2FUVXJi0CjmCapSmO7SnpJef0486qhLnuZ2cdeRhO02iuK6FUUVM" crossorigin="anonymous">
  <link rel="stylesheet" href="./static/style.css">

  <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

  <div class="container">
    <div class="row">
      <div class="col">
        <img class="img-fluid logo" src="../Escap-e/images/escape-logo-transparent.png" alt="logo">
      </div>
    </div>
  </div>

</head>

<body>
  <section class="adventure">
    <h2>Adventure Awaits<span>:</span></h2>
  </section>
  <div class="container searchcontainer">
    <div id="content">
      <nav class="navbar navbar-expand-lg navbar-light bg-light">
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
            <a class="nav-link active" href="#">Hotels</a>
            <a class="nav-link" href="#">Flights</a>
            <a class="nav-link" href="#">Cruises</a>
            <a class="nav-link" href="#">Cars</a>
        </div>
      </nav>
    </div>
  </div>
  <div id="mobileContent" style="display: none;">
    <div class="dropdown-wrapper">
      <div class="dropdown-header">
        <span class="arrow">&#9660;</span>
      </div>
      <ul class="dropdown-list">
        <li>Hotels</li>
        <li>Flights</li>
        <li>Cruises</li>
        <li>Cars</li>
      </ul>
    </div>
  
  </div>
    
      
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha3/dist/js/bootstrap.bundle.min.js"
  integrity="sha384-ENjdO4Dr2bkBIFxQpeoTz1HIcje39Wm4jDKdf19U8gI4ddQ3GYNS7NTKfAdVQSZe"
  crossorigin="anonymous"></script>
  <script src="./static/javascript.js"></script>
</body>

</html>
-->
### Developing Recipe Site
This site is a little more advanced on both deptarments, I again was tasked with constructing the whole site.

<!--
<!doctype html>
<html lang="en">

<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Foodery</title>
    <!--BOOTSTRAP CSS-->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.0/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-gH2yIJqKdNHPEq0n4Mqa/HGKIhSkIHeL5AyhkYV8i59U5AR6csBvApHHNl/vI1Bx" crossorigin="anonymous">
    <!--CUSTOM CSS-->
    <link href="static/foodery.css" rel="stylesheet">
    <link href="static/foodery-media-queries.css" rel="stylesheet">
    <!--FONTAWESOME-->
    <script src="https://kit.fontawesome.com/c0319300c2.js" crossorigin="anonymous"></script>
    <div class="hero-banner">
        <nav id="navbar" class="navbar">
            <div class="logo">
            <h3>Foodery</h3>
    </div>
    <ul class="menu">
        <li class="dropdown">
            <a class="dropdown-toggle" href="#">&#9776;</a>
                <ul class="dropdown-menu">
                    <a class="dropdown-item" href="#">Action</a>
                    <a class="dropdown-item" href="#">Another action</a>
                    <a class="dropdown-item" href="#">Something else here</a>
                </ul>
            </li>
        </ul>
    </ul>
    </nav>
    </div>
        <br>
        <br>
        <div class="heading">
            <h2>Simple Recipes to save you time and money!</h2>
            <p>Satisfy your cravings with our wide selection of simple and fast recipes. </p>
        </div>

      </head>

      <body>
    <div class="content1">
        <div class="container">
            <img src="../Foodery/images/salmon-bowl.jpg" alt="bowl of salmon">
        </div>
        <section class="featured">
            <h1>Featured</h1>
            <div class="featured-card">
                <img src="../Foodery/images/vegan-ramen.jpg" alt="vegan-ramen bowl" style="width: 35%; height: auto;">
                <div class="content1">
                    <h2>Vegan Ramen</h2>
                    <div class="button-container">
                    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Maecenas a nisl elit. Nunc dapibus sit amet mi non malesuada. Nam sit amet volutpat erat. Class aptent taciti sociosqu ad litora torquent per conubia nostra, per inceptos himenaeos. Mauris varius libero in mollis ultrices. Etiam odio ante, commodo vitae magna a, ornare malesuada odio. Proin facilisis ante ac elit hendrerit dapibus. Nunc et tincidunt mi. Morbi tincidunt felis non purus rhoncus, quis iaculis urna vehicula. Fusce aliquet mi risus, ut volutpat ipsum fringilla sed.</p>
                    <button class="view-recipe-button btn btn-primary">View Recipe</button>
                    </div>
                </div>
            </div>

            <div class="messages-bar bg-sucess">
                <div class="button-container">
                    <button id="like-button" class="view-recipe-button btn btn-primary"><i class="fa fa-heart" style="color:red"></i></button>
                    <span id="like-counter"></span>
                </div>
                <span class="message-icon"><i class='far fa-comment-alt'></i></span>
            </div>
        </section>

        <section class="newsletter-section">
            <div class="container">
                <h2>Newsletter</h2>
                <p class="text-dark">Subscribe to our newsletter to recieve updates!</p>
                <form id="newsletter-form" action="https://formspree.io/f/xvojpwpl" method="POST">
                    <input type="email" id="email-input" placeholder="Enter your email" required>
                    <button type="submit" class="submit-button btn btn-primary">Subscribe</button>
                </form>
            </div>
        </section>
    </div>

    <!--Footer-->
    <footer class="footer mt-auto py-3">
        <div class="container">
            <div class="row">
                <div class="col footer-text">
                    &copy; Foodery 2025, All rights reserved.
                </div>
                <div class="col text-right">
                    <a href="#">Home</a>
                    <a href="#">Featured</a>
                </div>
            </div>
        </div>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.0/dist/js/bootstrap.bundle.min.js"
        integrity="sha384-A3rJD856KowSb7dwlZdYEkO39Gagi7vIsF0jrRAoQmDKKtQBHUuLZ9AsSv4jD4Xa"
        crossorigin="anonymous"></script>
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.6.0/jquery.min.js"></script>
    <!--JAVASCRIPT LINK-->
    <script src="static/foodery.js"></script>
    </body>

    </html>
    -->
### Front End Stlying
For both projects css styling was absolutely necessary to reach the desired look of our projects.

Here's a snippit for the first site,
<!--
:root{
    --main-color: #1E1E1E;
    font-family: sans-serif; /*Fallback font for old browsers */
    font-family: var(--common-font);
}

body{
    color: var(--main-color);
    background-image: url("../images/calming-mountians.jpg");
    background-repeat: no-repeat;
    background-size: cover;
    background-attachment: fixed;
    background-position: center;
}

.logo {
    width: 125px;
    height: auto;
    position: absolute;
    padding: 10px;
}

@media only screen and (max-width: 600px) {
    .logo {
        width: 200px;
        height: auto;
        position: absolute;
        left: 50%;
        transform: translateX(-50%);
        padding: 10px;
        top: 15%;
    }
}

nav {
    display: inline-block;
    box-shadow: 0px 0px 15px 0px;
    opacity: .75;
    margin: auto;
    width: 50%;
    border-radius: 35px;
    vertical-align: middle;
}

.adventure {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 65vh;
}

h2 {
    text-align: center;
}

h2 span {
    color: red;
    font-size: 40px;
}

.searchcontainer {
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    position: absolute;
}

.navbar {
    padding-left: 15px;
    padding-right: 15px;
}
#navbarNavAltMarkup {
    justify-content: space-evenly;
    flex-grow: 1;
    font-weight: bold;
    font-size: larger;
}

-->

And snippit #2, 

<!--
#navbar {
    align-items: center;
    background-color: #f0f0f0;
    padding: 10px;
    display: flex;
    justify-content: space-between;

}

#navbar ul {
    list-style-type: none;
    margin: 0;
    padding: 0;
    overflow: hidden;
}

#navbar li {
    display: table-cell;
}

#navbar li a {
    display: flex;
    color: #333;
    text-align: center;
    padding: 14px 16px;
    text-decoration: none;
    flex-grow: 1;
    justify-content: center;
    align-items: center;
}

.sticky {
    position: fixed;
    top: 0;
    width: 100%;
}

#navbar li a:hover {
    background-color: black;
    color: lightgreen;
}

.hero-banner {
    position: relative;
}

.hero-text {
    font-size: 24px;
    line-height: 1.5;
    padding: 20px;
    text-align: center;
}

.featured-card {
    display: flex;
    align-items: center;
    margin-bottom: 20px;
    background-color: lightgreen;
    border-radius: 5px;
    overflow: hidden;
}

.featured-card .image {
    flex: 0 0 50%;
    border-top-left-radius: 5px;
    border-bottom-left-radius: 5px;
}

.featured-card .content1 {
    flex: 1;
    padding: 15px;
    max-width: calc(100% - 50%);
    overflow-wrap: break-word;
}

.featured-card h2 {
    margin-top: 0;
    font-size: 20px;
    color: #333;
}

.featured-card p {
    margin-bottom: 10px;
}

.featured-card .button-container {
    justify-content: center;
    gap: 10px;
    align-items: center;
    display: flex;
}

.featured-card .view-recipe-button {
    background-color: var(--main-color);
    color: white;
    padding: 10px 20px;
    border: none;
    border-radius: 5px;
    transition: background-color 0.3s ease;
}

-->


*Jump to: [Developing Travel Site](Developing-travel-site), [Developing Recipe Site](#Developing-recipe-site), [Page Top](#live-project)*
