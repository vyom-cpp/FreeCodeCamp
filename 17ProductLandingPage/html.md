```html
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>Product Landing Page</title>
        <link rel="stylesheet" href="styles.css">
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width, initial-scale="1.0">
        <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:opsz,wght,FILL,GRAD@48,400,1,0" />
    </head>
    <body>
        <script src="https://cdn.freecodecamp.org/testable-projects-fcc/v1/bundle.js"></script>
        <header id="header">
            <img src="https://cdn.freecodecamp.org/testable-projects-fcc/images/product-landing-page-logo.png" alt="logo" id="header-img">
            <nav id="nav-bar">
                <ul>
                    <li><a href="#features" class="nav-link">Features</a></li>
                    <li><a href="#process" class="nav-link">Process</a></li>
                    <li><a href="#pricing" class="nav-link">Pricing</a></li>
                </ul>
            </nav>
        </header>
        <form id="form" method="post" action="https://www.freecodecamp.com/email-submit">
            <p>Handcrafted, home-made masterpieces</p>
            <input type="email" id="email" placeholder="Enter your email address" required name="email">
            <input type="submit" value="GET STARTED" id="submit">
        </form>
        <main id="main">
            <section id="feature">
                <div class="feature">
                    <span class="material-symbols-outlined">inventory</span>
                        <div class="description" id="features">
                            <h1>Premium Materials</h1>
                            <p>Our trombones use the shiniest brass which is sourced locally. This will increase the longevity of your purchase.</p>
                        </div>
                </div>
                <div class="feature">
                    <span class="material-symbols-outlined">local_shipping</span>
                        <div class="description">
                            <h1>Fast Shipping</h1>
                            <p>We make sure you recieve your trombone as soon as we have finished making it. We also provide free returns if you are not satisfied.</p>
                        </div>
                </div>
                <div class="feature">
                    <span class="material-symbols-outlined">recommend</span>
                        <div class="description">
                            <h1>Quality Assurance</h1>
                            <p>For every purchase you make, we will ensure there are no damages or faults and we will check and test the pitch of your instrument.</p>
                        </div>
                </div>
            </section>
            <section id="process">
                <iframe src="https://youtu.be/y8Yv4pnO7qc" autoplay id="video"></iframe>
            </section>
        </main>
        <section id="pricing">
            <div class="box">
                <h2>TENOR TROMBONE</h2>
                <h3>$600</h3>
                <p>lorem ipusm<br/>lorem ipsum<br/>lorem ipusm.</p>
                <button id="btn">SELECT</button>
            </div>
            <div class="box">
                <h2>BASS TROMBONE</h2>
                <h3>$900</h3>
                <p>lorem ipusm<br/>lorem ipsum<br/>lorem ipusm.</p>
                <button id="btn">SELECT</button>
            </div>
            <div class="box">
                <h2>VALVE TROMBONE</h2>
                <h3>$1200</h3>
                <p>lorem ipusm<br/>lorem ipsum<br/>lorem ipusm.</p>
                <button id="btn">SELECT</button>
            </div>
        </section>
    </body>
</html>
```