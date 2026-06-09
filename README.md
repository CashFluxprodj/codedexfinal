# codedexfinal
final restruant project

<!DOCTYPE html>
<html>
    <head>
        <title>Pizza pizza</title>
    </head>
    <body>
        <header>
            <h1>Pizza pizza</h1>
            <figure>
                <img src="https://picsum.photos/300/150" alt="Placeholder img" id="header-ing">
            </figure>
            <nav>
                <ul>
                    <li>
                        <a href="#menu">Meny</a>
                    </li>
                    <li>
                        <a href="#order">order</a>
                    </li>
                </ul>
            </nav>
        </header>
        <main>
            <section id="menu">
                <h2>Our menu!</h2>
                <article>
                    <h3>Single pizza</h3>
                    <figure>
                        <img src="https://storage.pizzapizza.ca/phx2/ppl_images/products/en/2x/XXLCHZ.png?cache_key=1" alt="Single pizza">
                    </figure>
                    <p>
  Create your own single pizza with your choice of crust, toppings, and sauces. <i>Starting from $8.29.</i>
</p>
<br>
<hr>
                </article>
                <article>
                    <h3>Party pizza</h3>
                    <figure>
                        <img src="https://storage.pizzapizza.ca/phx2/ppl_images/products/en/2x/PTY.png?cache_key=1" alt="Paryt pizza">
                    </figure>
                    <p> Enjoy a large party-sized pizza made with custom toppings, perfect for sharing with a group. <i>Starting from $24.09</i>/p>
                </article>
                <br>
                <hr>
                <article>
                    <h3>Stuff crused pizza!</h3>
                    <figure>
                        <img src="https://storage.pizzapizza.ca/phx2/ppl_images/products/en/2x/LSTCR.png?cache_key=1" alt="Stuff Crused Pizza">
                       
                    </figure>
                    <p> Try a stuffed crust pizza filled with gooey melted mozzarella and your choice of toppings. <i>Starting from $15.29.</i> </p>
                </article>
                <br>
                <hr>
            </section>
            <Section id="order">
                <form>
                    <label for="single-pizza">How many single pizza?</label>
                    <input type="number" name="single-pizza" id="single-pizza" value="0" min="0">
                    <br>
                    <br>
                    <label for="party-pizza">How many Party Pizzas?</label>
                    <input type="number" name="party-pizza" id="party-pizza" value="0" min="0">
                    <br>
                    <br>
                    <label for="stuff-crused">How many Stuff Crused?</label>
                    <input type="number" name="stuff-crused" id="stuff-crused" value="0" min="0">
                    <br>
                    <br>
                    <label for="peperroni">peperroni</label>
                    <input type="checkbox" name="Toppings" id="peperroni" value="peperroni">
                    <label for="olives">olives </label>
                    <input type="checkbox" name="toppings" id="olives" value="olives">
                    <label for="peppers"Peppers>Peppers</label>
                    <input type="checkbox" name="toppings" id="peppers" value="peppers">
                    <br>
                    <hr>]
                    <h3>Special itmes!</h3>
                    <label for="special-requusts"></label>
                    <textarea name="special-requusts" id="special-requusts"></textarea>
                    <br>
                    <br>
                    <br>
                    <label for="checkout"></label>
                    <input type="button" name="checkout" id="checkout" type="submit" value="Go To Checkout">

                </form>
            </Section>
        </main>
    </body>
</html>
