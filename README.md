<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <link rel="stylesheet" href="bulma.css">
    <link rel="stylesheet" href="style.css">
    <title>Document</title>
</head>

<body>
    <nav class="navbar" role="navigation" aria-label="main navigation" style="background-color: black">
        <div class="navbar-brand">
            <a class="navbar-item" href="#">
                <img src="res/as.jpeg">
            </a>

            <a role="button" class="navbar-burger burger" aria-label="menu" aria-expanded="false" data-target="navbarBasicExample">
                <span aria-hidden="true"></span>
                <span aria-hidden="true"></span>
                <span aria-hidden="true"></span>
            </a>
        </div>

        <div id="navbarBasicExample" class="navbar-menu">
            <div class="navbar-start">
                <a class="navbar-item" href="index.html">
                    Home
                </a>

                <a class="navbar-item" href="documentation.html">
                    Documentation
                </a>

                <div class="navbar-item has-dropdown is-hoverable">
                    <a class="navbar-link">
                        More
                    </a>

                    <div class="navbar-dropdown">
                        <a class="navbar-item">
                            About
                        </a>
                        <a class="navbar-item">
                            Jobs
                        </a>
                        <a class="navbar-item">
                            Contact
                        </a>
                        <hr class="navbar-divider">
                        <a class="navbar-item">
                            Report an issue
                        </a>
                    </div>
                </div>
            </div>
        </div>
    </nav>

    <div class="isi" style="background-image: url(res/hand.jpg);">
        <br>
        <div class="container" style="height: 100%;">
            <div class="box" style="background-color: rgba(255, 255, 255, 0.5);">
                <div class="container">
                    IDENTITY COFFEE.

                    Coffee Shop yg menyediakan berbagai macam kopi etnik lokal dengan cita rasa internasional
                    
                </div>
            </div>
        </div>
        <br>
    </div>

    <footer class="footer" style="background-color: black">
        <div class="columns">
            <div class="column">
                <figure class="image" style="width: 250px; height: auto">
                    <img src="res/as.jpeg" alt="">
                </figure>
            </div>
            <div class="column">
                <strong>Bulma</strong> by <a href="https://jgthms.com">Jeremy Thomas</a>. The source code is licensed
                <a href="http://opensource.org/licenses/mit-license.php">MIT</a>. The website content
                is licensed <a href="http://creativecommons.org/licenses/by-nc-sa/4.0/">CC BY NC SA 4.0</a>.
            </div>
            <div class="column">
                <center>
                    <label class="label has-text-white">Find Us On</label>
                    <figure class="box image is-128x128">
                        <img src="res/qr.png" alt="">
                    </figure>
                </center>
            </div>
        </div>
    </footer>
</body>

</html>
