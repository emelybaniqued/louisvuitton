<!DOCTYPE html>
<html>
  <head>
    <link rel="stylesheet" href="styles.css" />
    <link
      rel="stylesheet"
      href="https://use.fontawesome.com/releases/v5.8.1/css/all.css"
      integrity="sha384-50oBUHEmvpQ+1lW4y57PTFmhCaXp0ML5d60M1M7uH2+nqUivzIebhndOJK28anvf"
      crossorigin="anonymous"
    />
  </head>
  <body>
    <div id="page-wrapper">
      <header id="header">
        <div class="logo">
          <img
            id="header-img"
            src="https://upload.wikimedia.org/wikipedia/commons/e/ec/Louis_Vuitton_logo.png"
            alt="louis vuitton"
          />
        </div>

        <nav id="nav-bar">
          <ul>
            <li><a class="nav-link" href="#features">Features</a></li>
            <li><a class="nav-link" href="#how-it-works">How It Works</a></li>
            <li><a class="nav-link" href="#pricing">Pricing</a></li>
          </ul>
        </nav>
      </header>

      <div class="container"></div>

      <section id="hero">
        <h2>Handcrafted, Quality, High Class Material</h2>
        <form id="form" action="https://www.freecodecamp.com/email-submit">
          <input
            name="email"
            id="email"
            type="email"
            placeholder="Enter your email address"
            required
          />
          <input id="submit" type="submit" value="Get Started" class="btn" />
        </form>
      </section>

      <div class="container">
        <section id="features">
          <div class="grid">
            <div class="icon"><i class="fa fa-3x fa-fire"></i></div>
            <div class="desc">
              <h2>Premium Materials</h2>
              <p>
                Our material our sourced in a original material, Handcrafted and built with quality and class.
              </p>
            </div>
          </div>
          <div class="grid">
            <div class="icon"><i class="fa fa-3x fa-truck"></i></div>
            <div class="desc">
              <h2>Fast Shipping</h2>
              <p>
                We make sure you recieve your Louis vuitton as soon as we have
                finished making it. We also provide free returns if you are not
                satisfied.
              </p>
            </div>
          </div>
          <div class="grid">
            <div class="icon">
              <i class="fa fa-3x fa-battery-full" aria-hidden="true"></i>
            </div>
            <div class="desc">
              <h2>Quality Assurance</h2>
              <p>
                For every purchase you make, we will ensure there are no damages
                or faults and we will check the quality of every product
              </p>
            </div>
          </div>
        </section>
        <section id="how-it-works">
          <iframe
            id="video"
            height="315"
            src="https://www.youtube.com/embed/8HI4j7Lillk"
            frameborder="0"
            allowfullscreen
          ></iframe>
        </section>
        <section id="pricing">
          <div class="product" id="tenor">
            <div class="level">Fragrances</div>
            <h2>$800</h2>
            <ol>
              <li>For Women</li>
              <li>For Men</li>
              <li>Classic</li>
              <li>Premuim</li>
            </ol>
            <button class="btn">Select</button>
          </div>
          <div class="product" id="bass">
            <div class="level">Jewelry</div>
            <h2>$1000</h2>
            <ol>
              <li>High Standard</li>
              <li>Expensive Gold</li>
              <li>Classic</li>
              <li>Premium</li>
            </ol>
            <button class="btn">Select</button>
          </div>
          <div class="product" id="valve">
            <div class="level">Bags</div>
            <h2>$2000</h2>
            <ol>
              <li>Originam Material</li>
              <li>Quality Made</li>
              <li>Premuim</li>
              <li>Hand Made</li>
            </ol>
            <button class="btn">Select</button>
          </div>
        </section>
        <footer>
          <ul>
            <li><a href="#">Privacy</a></li>
            <li><a href="#">Terms</a></li>
            <li><a href="#">Contact</a></li>
          </ul>
          <span>Copyright 2016, Louis Vuitton</span>
        </footer>
      </div>
    </div>
  </body>
</html>
