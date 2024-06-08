# cafe-menu
HTML and CSS codes to display a Cafe Menu

<!DOCTYPE html>
<html lang="en">
    <!--CSS code-->
    <style>
        /*CSS code for the Project "Cafe Menu" */
/*h1, h2, p: Coffee*/
h1, h2, p{
    text-align: center;
}

/*h1, h2 fonts*/
h1, h2{
    font-family: Impact, serif; /*fallbacks: in instances where the initial font is not found/available*/
}

/*h1, h2 font-size*/
h1{
    margin-top: 0;
    margin-bottom: 15px;
    font-size: 40px;
}

h2{
    font-size: 30px;
}

/*to style Est. 2020*/
.established{
    font-style: italic;
}

/*Coffee Image*/
img{
    display: block;
    margin-top: -25px;
    margin-left: auto;
    margin-right: auto;
}

hr{
    height: 2px; /*border-width default value is 1px for all edges*/
    background-color: brown;
    border-color: brown; /*Edges, borders of the hr*/
}

/*For second hr*/
.bottom-line{
    margin-top: 25px;
}

/*Body*/
body{
    background-image: url(https://cdn.freecodecamp.org/curriculum/css-cafe/beans.jpg);
    font-family: sans-serif;
    padding: 20px;
}

/*Id=Menu*/
.menu{
    max-width: 500px; /*sets this div to make it 80% the width of body, not the div*/
    background-color: burlywood;
    /*To center horizontally within the body element*/
    margin-left: auto;
    margin-right: auto;
    padding: 20px;
}

.dessert, .flavor{
    text-align: left;
    width: 75%;
}

.price{
    text-align: right;
    width: 25%;
}

    /*p behave as inline elements*/
.item p{
    font-size: 18px;
    display: inline-block;
    margin-top: 5px;
    margin-bottom: 5px;
}

/*Footer*/
footer{
    font-size: 14px;
}

footer a:visited{ /*when a webpage has being visited*/
    color: black;
}

footer a:hover{
    color: brown;
}

footer a:active{ /*when a link has being clicked*/
    color: brown;
}

a{
    color: black;
}

/*Address*/
.address{
    margin-bottom: 5px;
}
    </style>
    <body>
            <!--Div: For design layout purposes-->
            <!--Main Section-->
            <div class="menu">
            <main>
                <h1>CAMPER CAFE</h1>
                <p class="established">Est. 2020</p>
                <hr>
                <!--First Section-->
                <section>
                    <h2>Coffee</h2>
                    <img src="https://cdn.freecodecamp.org/curriculum/css-cafe/coffee.jpg" alt="coffee icon">
                    <!--Article: contains multiple elements that have related information-->
                      <article class="item">
                        <p class="flavor">French Vanilla</p><p class="price">$3.00</p>
                      </article>
                      <article class="item">
                        <p class="flavor">Caramel Macchiato</p><p class="price">$3.75</p>
                      </article>
                      <article class="item">
                        <p class="flavor">Pumpkin Spice</p><p class="price">$3.50</p>
                      </article>
                      <article class="item">
                        <p class="flavor">Hazelnut</p><p class="price">$4.00</p>
                      </article>
                      <article class="item">
                        <p class="flavor">Mocha</p><p class="price">$4.50</p>
                      </article>
                </section>
                <!--Second Section-->
                <section>
                    <h2>Desserts</h2>
                    <img src="https://cdn.freecodecamp.org/curriculum/css-cafe/pie.jpg" alt="pie icon">
                    <!--Article Section-->
                    <article class="item">
                        <p class="dessert">Donuts</p><p class="price">$1.50</p>
                    </article>
                    <article class="item">
                        <p class="dessert">Cherry Pie</p><p class="price">$2.75</p>
                    </article>
                    <article class="item">
                        <p class="dessert">Cheesecake</p><p class="price">$3.00</p>
                    </article>
                    <article class="item">
                        <p class="dessert">Cinnamon Roll</p><p class="price">$2.50</p>
                    </article>
                </section>
            </main>
            <hr class="bottom-line">
            <!--Footer-->
            <footer>
                <p>
                    <a href="https://www.freecodecamp.org" target="_blank">Visit our website</a>
                </p>
                <p class="address">
                    123 Free Code Camp Drive
                    BC, Canada
                </p>
            </footer>
            </div>
    </body>
</html>
