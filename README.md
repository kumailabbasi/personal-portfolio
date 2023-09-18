# personal-portfolio
this is my personal poortfolio
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>kumail- developer portfolio</title>

    <!-- font family sa uthaya ha poppins nam ka -->

    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet">
    <!-- awesome font cdn ka link ha -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.2/css/all.min.css">

    <!-- internal css start here -->

    <style>
        * {
            margin: 0px;
            padding: 0px;
        }
        
        body {
            background-color: whitesmoke;
            color: rgb(13, 12, 12);
            font-family: 'Poppins', sans-serif;
            max-height: max-content;
        }
        
        nav {
            display: flex;
            justify-content: space-around;
            align-items: center;
            height: 85px;
            background-color: rgb(27, 120, 117);
            color: rgb(228, 238, 248);
        }
        
        nav ul {
            display: flex;
            justify-content: center;
        }
        
        nav ul li {
            list-style: none;
            margin: 0px 23px;
        }
        
        nav ul li a {
            text-decoration: none;
            color: rgb(185, 14, 14);
        }
        
        nav ul li a:hover {
            color: blueviolet;
        }
        
        .right a {
            margin: 10px;
            padding: 15px;
            text-decoration: none;
            font-size: 1.9rem;
            color: white;
        }
        
        .firstsection {
            display: flex;
            justify-content: space-around;
            margin: 85px;
        }
        
        .firstsection div {
            width: 30%;
        }
        
        .leftsection {
            font-size: 2rem;
            padding: 10px;
            margin: 100px 0px;
            width: 100%;
            text-align: center;
            height: 80%;
        }
        
        .leftsection j {
            color: brown;
        }
        
        .leftsection b {
            color: blueviolet;
        }
        
        .rightsection img {
            width: 85%;
            margin: 0px 0px;
        }
        
        .rightsection h4 {
            text-align: center;
        }
        
        p {
            font-size: 18px;
        }
        
        .container {
            background-color: rgb(240, 246, 244);
        }
        
        .container h2 {
            color: rgb(0, 22, 100);
        }
        
        .container h3 {
            color: brown;
        }
        
        .left {
            color: white;
            font-size: 2rem;
        }
        
        .profile {
            text-align: right;
            font-size: 1rem;
            margin-left: 150px;
            padding: 70px;
        }
        
        .cont {
            text-align: center;
        }
    </style>



    <!-- internal css end -->

</head>

<!-- body start hoa ha -->

<body>

    <nav>
        <div class="left">kumail's-Portfolio</div>
        <div class="right">
            <ul>
                <!-- link lagaya ha -->
                <a href="http://127.0.0.1:5500/home.html">
                    <i class="fa-solid fa-house"></i>Home
                </a>
                <a href="http://127.0.0.1:5500/gallery.html">
                    <i class="fa-solid fa-image"></i>gallery
                </a>

                <a href="http://127.0.0.1:5500/">
                    <i class="fa-brands fa-r-project"></i>>my project
                </a>

                <a href="https://form.jotform.com/232512272390449">
                    <i class="fa-solid fa-comments"></i>feedback
                </a>
                <!-- link khatam nav ka -->
            </ul>
        </div>
    </nav>

    <main>
        <!-- description start tha wa -->
        <section class="firstsection">
            <div class="leftsection">Hii my name is
                <j>kumail abbasi</j> and i am passionate
                <br> <b id="animate"> web-developer.</b>
                <br><br>
                <hr>
            </div>

            <div class="rightsection">
                <img src="ac.jpg" alt="error">
                <h4>this is my office</h4>
                <hr>

            </div>


            <section class="profile">
                <h2>my personal id</h2>
                <p>you may visit now</p>
                <a href="https://www.facebook.com/profile.php?id=100065644086396&mibextid=ZbWKwL">facebook<i class="fa-brands fa-facebook"></i><br>></a>
                <a href="http://www.twitter.com/">  tiwiter<i class="fa-brands fa-twitter"></i><br></a>
                <a href="https://instagram.com/kumail.abbasi.948?utm_source=qr&igshid=MzNlNGNkZWQ4Mg==">instagram<i class="fa-brands fa-instagram"></i><br> </a>
                <a href=" https://wa.me/03464969245/"> watsapp <i class="fa-brands fa-whatsapp"></i><br> </a>
                <a href="https://kumailandtouragencybaltistan.travel.blog/"> My website<i class="fa-brands fa-google"></i><br></a>
                <br><br><br><br>
                <hr> </section>
        </section>
        <hr>
        </section>
        <hr>
        <hr>
        <hr>
        <div class="container">
            <section>
                <h2>About Me</h2>
                <p>Hello, my name is <b>kumail</b>, and today here I'm to introduce myself for the position of Software Developer in your company. I've previously worked ain tehsloab company and have a work experience of 2 month

                </p><br>
            </section>
            <!-- yhang sa mera projecct start ha -->
            <section>
                <h2>My Projects</h2>
                <div class="project">
                    <h3>Project 1</h3>
                    <p>"I specialize in creating websites using technologies like .NET, HTML, and CSS. I design and build user-friendly web interfaces that look great and work smoothly. Whether it's developing dynamic web applications or crafting responsive
                        layouts, I have a proven track record of delivering high-quality projects."</p>
                    <p> clink my simple website link </p>
                    <a href="https://groove.cm/go-c?aff_id=683946&gclid=CjwKCAjwjOunBhB4EiwA94JWsE9kqEB8t6DW-d3p8K6GeYaVq5uoKCTuy0PRaAGctmvtlr0NpMpqoxoCU7EQAvD_BwE#RT2MtEg_bO"><br>this is my first prroject <br></a>
                </div>

                <div class="project">
                    <h3>Project 2</h3>
                    <p>Recently i have recieved my master degree. i am woking in tehsolab company.and i know how ATTRACTIVE SOFTWARE can be build. i am professional software developer .
                    </p>
                    <p>my another web link</p>
                    <a href="https://tourism.gov.pk/"><br>this is my 2nd prroject <br>
                    </a>
                    <h3>project 3</h3>
                    <p>Also expert in gaming</p><br>
                    <p>many game like <b>car racing,dump bufallow </b>already created</p>
                    <p>my gaming website link</p>
                    <a href="https://gamesforlove.org/?gclid=CjwKCAjwjOunBhB4EiwA94JWsHCT0auFduiTAzqsetGwEVEN3loc8sOy2NvJA9e-MIc1ehXe25cSGhoC7QMQAvD_BwE"><br>this is my last prroject <br></a>
                </div><br><br>
            </section>
            <hr>
            <br><br>
            <section>
                <div class="cont">
                    <span>  <h2> contact me</h2></span>
                    <p>if you are intrested my work then you are higher me</p>

                    <form action="/action_page.php" autocomplete="on">
                        <label for="fname">First name:</label>
                        <input type="text" id="fname" name="fname"><br><br>
                        <label for="email">Email:</label>
                        <input type="text" id="email" name="email"><br><br>
                        <input type="submit">
                    </form>




                    <!-- last ka footer -->
                    <footer>
                        &copy; 2023 Your Name
                    </footer>
                </div>
            </section>
    </main>

    <script>
        var animate = document.getElementById("animate");
        var text = animate.innerText;
        var currentIndex = 0;

        function animateText() {
            if (currentIndex < text.length) {
                animate.innerText += text.charAt(currentIndex);
                currentIndex++;
            } else {
                currentIndex = 0;
                animate.innerText = "";
            }
        }

        // Call the animateText function at intervals (adjust the speed as needed)
        setInterval(animateText, 300); // Adjust the interval to control the typing speed
    </script>
</body>

</html>