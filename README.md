<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <link rel="preconnect" href="https://fonts.gstatic.com">
    <link href="https://fonts.googleapis.com/css2?family=Open+Sans:ital,wght@0,300;0,400;0,600;0,700;0,800;1,300;1,400;1,600;1,700;1,800&display=swap" rel="stylesheet">
    <title>lennard D</title>
</head>

<body>
    <div id="sidebar">
        <ul>
            <li>
                <a href="index.html">Home</a></li>
            <li>
                <a href="https://www.youtube.com/c/lennardd">YouTue</a></li>
            <li><a href="https://www.instagram.com/dobberlennard/">Instagram</a></li>
            <li> <a href="https://twitter.com/LennardD11">Twitter</a></li>

        </ul>
    </div>
    <div id="toggle-btn" onclick="toggleSidebar(this)">
        <span></span>
        <span></span>
        <span></span>
    </div>
    <script>
        function toggleSidebar(ref) {
            ref.classList.toggle('active');
            document.getElementById('sidebar').classList.toggle('active');
        }
    </script>

    <body>
        <div class="navbar">
            <h1 class="headline">
                Lennard D<br> <span class="text-highlight">YouTuber</span>
            </h1>

            <div>
                <a href="index.html">Home</a>
                <a href="https://www.youtube.com/c/lennardd">YouTue</a>
                <a href="https://www.instagram.com/dobberlennard">Instagram</a>
                <a href="https://twitter.com/LennardD11">Twitter</a>
                <a href="#">info</a>
            </div>
        </div>



        <div class="image-container">
            <img class="header-image" src="header.jpg">

            <div class="text-container">

            </div>


            <div class="maps-container">

                <iframe class="maps-frame" width="560" height="315" src="https://www.youtube.com/embed/oQF91cDDvVA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen> 
                    allowfullscreen="" loading="lazy"></iframe>

                <div class="text-container maps-right">
                    Hallo... Herzlich willkommen auf meime Website. viel spaß auf mein website.
                </div>
            </div>

        </div>

        <div class="legal-content">
            <span class="legal-text">(c) 2022 - Imaginary Company GmbH</span> | <a href="#">Impressum</a> | <a href="#">Datenschutz</a>
        </div>
    </body>
</body>

</html>
