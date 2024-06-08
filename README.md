# cafe-menu
HTML and CSS codes to display a Cafe Menu

<!DOCTYPE html>
<html lang="en">
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
