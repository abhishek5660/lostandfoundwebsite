<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>lost and found</title>
    <!-- 
    - favicon
  -->
    <link rel="shortcut icon" href="./icon.svg" type="image/svg+xml">
    <!-- 
    - custom css link
  -->
    <link rel="stylesheet" href="./assets/css/style.css">
    <!-- .5
        6
    - google font link   
  -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600&family=Source+Sans+Pro:wght@600;700&display=swap" rel="stylesheet">
</head>
<body id="top">
    <!-- 
    - #HEADER
  -->
    <header class="header" data-header>
        <div class="container">
            <div class="overlay" data-overlay></div>
            <a href="#">
                ✿
                <h1 class="logo">LOST & FOUND</h1>
            </a>
            <nav class="navbar" data-navbar>
                <div class="navbar-top">
                    <a href="#" class="logo">Lost & Found</a>
                    <button class="nav-close-btn" aria-label="Close Menu" data-nav-close-btn>
            <ion-icon name="close-outline"></ion-icon>
          </button>
                </div>
                <ul class="navbar-list">
                    <li class="navbar-item">
                        <a href="" class="navbar-link" data-navbar-link>Home</a>
                    </li>
                    <li class="navbar-item">
                        <a href="http://127.0.0.1:5500/lostitem.html" class="navbar-link" data-navbar-link>Lost item</a>
    </li>
</li>
<li class="navbar-item">
    <a href="http://127.0.0.1:5500/founditem.html" class="navbar-link" data-navbar-link>Found item</a>
</li>
                    <li class="navbar-item">
                        <a href="http://127.0.0.1:5500/auth.html" class="navbar-link" data-navbar-link>login</a>
                    </li>
                </li>  
                    <li class="navbar-item">
                        <a href="http://127.0.0.1:5500/contactus.html" class="navbar-link" data-navbar-link>Contact Us</a>
              </li>
            </ul>                   
            </nav>
            
            <a href="http://127.0.0.1:5500/profile.html" class="btn">
                <ion-icon name="chevron-forward-outline" aria-hidden="true"></ion-icon>

                <span>User Profile</span>
            </a>

            <button class="nav-open-btn" aria-label="Open Menu" data-nav-open-btn>
        <ion-icon name="menu-outline"></ion-icon>
      </button>

        </div>
    </header>
    <main>
        <article>

            <!-- 
        - #HERO
      -->
            <section class="hero" id="home">
                <div class="container">

                    <div class="hero-content">

                        <p class="hero-subtitle">The Lost and Found App makes your life easier.</p>

                        <h2 class="h2 hero-title">LOST ITEM SOLUTION</h2>
          
                        <p class="h2 hero-text">
                            Returning Lost Items Back To Their Owners Quickly And Seamlessly.
                        </p>

                        <button class="btn"><a href="http://127.0.0.1:5500/googlemap.html" class="navbar-link" data-navbar-link>Location</button></a>
                    </div>

                    <figure class="hero-banner">    
                        <img src="https://i.pinimg.com/originals/42/0d/73/420d73f8499b2ae96eb3aab67973598d.jpg" width="494" height="329" loading="lazy" alt="hero-banner" class="w-80 banner-animation">
                    </figure>
                </div>
            </section>
            <!--        
        - #ABOUT
            -->
            <section class="section about" id="about">
                <div class="container">

                    <figure class="about-banner">
                        <img src="https://codewithsadee.github.io/desinic/assets/images/about-banner.png" width="700" height="532" loading="lazy" alt="about banner" class="w-100 banner-animation">
                    </figure>
                    <div class="about-content">
                        <h2 class="h2 section-title underline">Why Our Lost&Found</h2>
                        <p class="about-text">
                            The world right now is distracted. People are always checking their phones every few minutes or lost in thought about personal and career problems. The management of your lost and found department can break or build your customers’ trust. Lost and found software provides a solution. It makes the management of these items smooth, without breaking your budget.
                        </p>
                        <p class="about-text">
                            Losing a property, especially if it’s of sentimental value, causes emotional turmoil. The last thing your agitated customer needs is false hope.
                        </p>
                        <ul class="stats-list">

                            <li class="stats-card">
                                <p class="h3 stats-title">000</p>

                                <p class="stats-text">Satisfied Clients</p>
                            </li>

                            <li class="stats-card">
                                <p class="h3 stats-title">2024</p>

                                <p class="stats-text">Project Lunched</p>
                            </li>

                            <li class="stats-card">
                                <p class="h3 stats-title">00</p>
                                <p class="stats-text">Years Completed</p>
                            </li>

                        </ul>

                    </div>

                </div>
            </section>
            <!-- 
        - #SERVICE
      -->\
            <section class="section service" id="services">
                <div class="container">

                    <h2 class="h2 section-title underline">HOW IT WORKS ?</h2>

                    <ul class="service-list">

                        <li>
                            <div class="service-card">

                                <div class="card-icon">
                                    <ion-icon name="telescope-outline"></ion-icon>
                                </div>

                               <a href="http://127.0.0.1:5500/PROJECT-1/auth.html"> <h3 class="h3 title">Create an account</h3></a>

                                <p class="text">
                                    Initially, you have create an account to get started
                                </p>

                                <button class="card-btn" aria-label="Show More">
                  <ion-icon name="chevron-forward-outline"></ion-icon>
                </button>
                            </div>
                        </li>

                        <li>
                            <div class="service-card">                              

                                <div class="card-icon">
                                    <ion-icon name="desktop-outline"></ion-icon>
                                </div>

                                <h3 class="h3 title">lost/Find items</h3>
                                

                                <p class="text">
                                List your item on the wall by falling certain details and image. That's it!
                                </p>

                                <button class="card-btn" aria-label="Show More">
                  <ion-icon name="chevron-forward-outline"></ion-icon>
                </button> 
                            </div>
                        </li>
                        <li>
                            <div class="service-card">  

                                <div class="card-icon">
                                    <ion-icon name="globe-outline"></ion-icon>
                                </div>
   
                               <a href="http://127.0.0.1:5500/notification.html"> <h3 class="h3 title">Get Notified</h3></a>
                                <p class="text">
                                    Once anyone posts an item, we make our registed users aware about the same by sending notifications.
                                </p>
                                <button class="card-btn" aria-label="Show More">
                  <ion-icon name="chevron-forward-outline"></ion-icon>
                </button>
                            </div>
                        </li>

                    </ul>

                </div>
            </section>


            <!-- 
        - #FEATURES
      -->

    <section class="section features" id="features">
                <div class="container">

                    <h2 class="h2 section-title underline">Our Features</h2>

                    <ul class="features-list">

                        <li>
                            <div class="features-card">

                                <div class="icon">
                                    <ion-icon name="bulb-outline"></ion-icon>
                                </div>

                                <div class="content">
                                    <h3 class="h3 title">LOST ITEM</h3>

                                    <p class="text">
                                        Common law defines lost property as personal property that was unintentionally left by its true owner. For example, a wallet that falls out of someone's pocket is lost. At common law, a person who found lost personal property could keep it until and unless the original owner comes forward.
                                    </p>
                                </div>

                            </div>
                        </li>

                        <li>
                            <div class="features-card">

                                <div class="icon">
                                    <ion-icon name="color-palette-outline"></ion-icon>
                                </div>

                                <div class="content">
                                    <h3 class="h3 title">Feedback</h3>

                                    <p class="text">
                                        The plot was predictable, something that made the movie boring and in many moments I was just trying to find a reason to continue watching it. loremipsum   loremipsum   loremipsum   loremipsum   loremipsum   loremipsum   loremipsum 
                                    </p>
                                </div>

                            </div>
                        </li>

                    </ul>

                    <figure class="features-banner">
                        <img src="https://codewithsadee.github.io/desinic/assets/images/feautres-banner.png" width="369" height="318" loading="lazy" alt="Features Banner" class="w-100 banner-animation">
                    </figure>

                    <ul class="features-list">

                        <li>
                            <div class="features-card">

                                <div class="icon">
                                    <ion-icon name="code-slash-outline"></ion-icon>
                                </div>

                                <div class="content">
                                    <h3 class="h3 title">FOUND ITEM</h3>

                                    <p class="text">
                                        You can use phone, email, or social media to contact the guest, or wait for them to contact you. You should verify their identity and ownership of the item, and ask them how they prefer to receive it. 
                                    </p>
                                </div>
                            </div>
                        </li>

                        <li>
                            <div class="features-card">

                                <div class="icon">
                                    <ion-icon name="rocket-outline"></ion-icon>
                                </div>

                                <div class="content">
                                    <h3 class="h3 title">Testing & Lunching</h3>

                                    <p class="text">
                                        Visual Studio Code is a free coding editor that helps you start coding quickly. Use it to code in any programming language, without switching editors. Visual Studio Code has support for many languages, including Python, Java, C++, JavaScript, and more.
                                    </p>
                                </div>
                            </div>
                        </li>
                    </ul>
                </div>
            </section>
            <!-- 
        - #BLOG
      -->
            <section class="section blog" id="blog">
                <div class="container">

                    <h2 class="h2 section-title underline">Our Blog & News</h2>

                    <ul class="blog-list">

                        <li>
                            <div class="blog-card">

                                <figure class="banner">
                                    <a href="">
                    <img src="https://media.istockphoto.com/id/1739381148/vector/lost-items-icon-lost-and-found.jpg?s=612x612&w=0&k=20&c=cfMKPPNCCI-R95iEBcALlkCbgBVPj5smE7RG1aRRAcU=" width="750" height="350" loading="lazy"
                      alt="Vestibulum massa arcu, consectetu pellentesque scelerisque." class="img-cover">
                  </a>
                 </figure>
                <div class="content">
                        <h3 class="h3 title">
                                        <a href="#">
                                            Lost And Found Real-Time Object Detection
                    </a>
                                    </h3>
                                    <p class="text">
                                        We are proud to present the first working prototype of our “Real Time Object Detection? function.
                                    </p>

                                    <div class="meta">
                                        <div class="publish-date">
                                            <ion-icon name="time-outline"></ion-icon>

                                            <time datetime="2022-03-07"> 9 feb, 2024 </time>
                                        </div>
                                        <button class="comment" aria-label="Comment">
                      <ion-icon name="chatbubble-outline"></ion-icon>
                      <data value="15">15</data>
                                        </button>
                                        <button class="share" aria-label="Share">
                      <ion-icon name="share-social-outline"></ion-icon>
                    </button>
                                    </div>
                                </div>
                            </div>
                        </li>
                        <li>
                            <div class="blog-card">

                                <figure class="banner">
                                    <a href="#">
                    <img src="https://media.istockphoto.com/id/477273563/vector/lost-found-box.jpg?s=612x612&w=0&k=20&c=D63_IrCalWqRLpYCnBA5b5QTfhxwbSggkxLiw7vQGGs=" width="750" height="350" loading="lazy"
                      alt="Quisque egestas iaculis felis eget placerat ut pulvinar mi." class="img-cover">
                  </a>
                                </figure>
                                <div class="content">               
                                    <h3 class="h3 title">
                                        <a href="#">
                                            Why is it called lost and found?
                    </a>
                                    </h3>

                                    <p class="text">
                                        It's items that someone lost and someone else found. The title helps people who have lost items to find out where they might find them.
                                    </p>

                                    <div class="meta">

                                        <div class="publish-date">
                                            <ion-icon name="time-outline"></ion-icon>

                                            <time datetime="2022-03-07">9 feb, 2024</time>
                                        </div>

                                        <button class="comment" aria-label="Comment">
                      <ion-icon name="chatbubble-outline"></ion-icon>

                      <data value="15">15</data>
                    </button>

                                        <button class="share" aria-label="Share">
                      <ion-icon name="share-social-outline"></ion-icon>
                    </button>

                                    </div>

                                </div>

                            </div>
                        </li>

                        <li>
                            <div class="blog-card">

                                <figure class="banner">
                                    <a href="#">
                    <img src="https://media.istockphoto.com/id/471374521/photo/lost-and-found-box.jpg?s=612x612&w=0&k=20&c=KHDtL0ZoQ-AoX_WIMRtXPc7R5CkJN_rC1atNsHjZdaQ=" width="750" height="350" loading="lazy"
                      alt="Fusce sem ligula, imperdiet sed nisi sit amet, euismod posuere." class="img-cover">
                  </a>
                                </figure>

                                <div class="content">

                                    <h3 class="h3 title">
                                        <a href="#">
                                            Can I found a person by photo?

                    </a>
                                    </h3>

                                    <p class="text">
                                        It is possible to try and find a person using a photo, but it may be difficult without additional information. 
                                    </p>

                                    <div class="meta">

                                        <div class="publish-date">
                                            <ion-icon name="time-outline"></ion-icon>

                                            <time datetime="2022-03-07">9 feb, 2024</time>
                                        </div>

                                        <button class="comment" aria-label="Comment">
                      <ion-icon name="chatbubble-outline"></ion-icon>

                      <data value="15">15</data>
                    </button>

                                        <button class="share" aria-label="Share">
                      <ion-icon name="share-social-outline"></ion-icon>
                    </button>

                                    </div>

                                </div>

                            </div>
                        </li>

                        <li>
                            <div class="blog-card">

                                <figure class="banner">
                                    <a href="#">
                    <img src="https://www.hillelementary.com/wp-content/uploads/2018/05/lostandfound.jpg" width="750" height="350" loading="lazy"
                      alt="Donec feugiat mollis nisi in dignissim. Morbi sollicitudin quis." class="img-cover">
                  </a>
                                </figure>

                                <div class="content">

                                    <h3 class="h3 title">
                                        <a href="https://en.wikipedia.org/wiki/Lost_and_found#:~:text=The%20first%20modern%20lost%20and,the%20office's%20director%20in%202001.">
                                            Who started lost and found?
                    </a>
                                    </h3>

                                    <p class="text">
                                        The first modern lost and found office was organized in Paris in 1805.
                                    </p>

                                    <div class="meta">

                                        <div class="publish-date">
                                            <ion-icon name="time-outline"></ion-icon>

                                            <time datetime="2022-03-07">9 feb, 2024</time>
                                        </div>

                                        <button class="comment" aria-label="Comment">
                      <ion-icon name="chatbubble-outline"></ion-icon>

                      <data value="15">15</data>
                    </button>

                                        <button class="share" aria-label="Share">
                      <ion-icon name="share-social-outline"></ion-icon>
                    </button>

                                    </div>

                                </div>

                            </div>
                        </li>

                    </ul>

                </div>
            </section>

        </article>
    </main>





    <!-- 
    - #FOOTER
  -->

    <footer class="footer">

        <div class="footer-top section">
            <div class="container">

                <div class="footer-brand">

                    <a href="#" class="logo">The Lost & Found</a>

                    <p class="text">
                        We created this app for anyone to handle Lost and Found. Over the last couple of years,
                         our team has built a Software and App using the latest web technologies in cooperation
                          with industry leaders from hospitality, aviation and public transportation.
                    </p>

                    <ul class="social-list">

                        <li>
                            <a href="https://www.facebook.com/" class="social-link">
                                <ion-icon name="logo-facebook"></ion-icon>
                            </a>
                        </li>

                        <li>
                            <a href="https://www.instagram.com/accounts/login/?hl=en" class="social-link">
                                <ion-icon name="logo-instagram"></ion-icon>
                            </a>
                        </li>

                        <li>
                            <a href="https://twitter.com/i/flow/login" class="social-link">
                                <ion-icon name="logo-twitter"></ion-icon>
                            </a>
                        </li>

                    </ul>

                </div>

                <ul class="footer-list">

                    <li>
                        <p class="footer-list-title">Our links</p>
                    </li>

                    <li>
                        <a href="#" class="footer-link">Home</a>
                    </li>

                    <li>
                        <a href="#" class="footer-link">About Us</a>
                    </li>

                    <li>
                        <a href="#" class="footer-link">Service</a>
                    </li>

                    <li>
                        <a href="#" class="footer-link">Team</a>
                    </li>

                    <li>
                        <a href="#" class="footer-link">Blog</a>
                    </li>

                </ul>

                <ul class="footer-list">

                    <li>
                        <p class="footer-list-title">Our site</p>
                    </li>

                    <li>
                        <a href="#" class="footer-link">Strategy & Research</a>
                    </li>

                    <li>
                        <a href="#" class="footer-link">Web Development</a>
                    </li>

                    <li>
                        <a href="#" class="footer-link">Web Solution</a>
                    </li>

                    <li>
                        <a href="#" class="footer-link">Lost and found</a>
                    </li>
                </ul>

                <ul class="footer-list">

                    <li>
                        <p class="footer-list-title">Other links</p>
                    </li>

                    <li>
                        <a href="#" class="footer-link">FAQ</a>
                    </li>

                    <li>
                        <a href="#" class="footer-link">Portfolio</a>
                    </li>

                    <li>
                        <a href="#" class="footer-link">Privacy Policy</a>
                    </li>

                    <li>
                        <a href="#" class="footer-link">Terms & Conditions</a>
                    </li>

                    <li>
                        <a href="#" class="footer-link">Support</a>
                    </li>

                </ul>

                <ul class="footer-list">

                    <li>
                        <p href="http://127.0.0.1:5500/contactus.html" class="footer-list-title">Contact Us</p>
                    </li>

                    <li class="footer-item">

                        <div class="footer-item-icon">
                            <ion-icon name="call"></ion-icon>
                        </div>

                        <div>
                            <a href="tel:7018594320" class="footer-item-link">+91 7018594320</a>
                            <a href="tel:8219472136" class="footer-item-link">+91 8219472136</a>
                            <a href="tel:8894384777" class="footer-item-link">+91 8894384777</a>
                        </div>

                    </li>

                    <li class="footer-item">

                        <div class="footer-item-icon">
                            <ion-icon name="mail"></ion-icon>
                        </div>

                        <div>
                            <a href="abhishek1013.be22@chitkarauniversity.edu.in" class="footer-item-link">abhishek1013.be22@chitkarauniversity.edu.in</a>
                            <a href="kartik1193.be22@chitkarauniversity.edu.in" class="footer-item-link">kartik1193.be22@chitkarauniversity.edu.in</a>
                            <a href="aditya1021.be22@chitkarauniversity.edu.in" class="footer-item-link">aditya1021.be22@chitkarauniversity.edu.in</a>
                        </div>

                    </li>

                    <li class="footer-item">

                        <div class="footer-item-icon">
                            <ion-icon name="location"></ion-icon>
                        </div>

                        <address class="footer-item-link">
              Himachal pradesh, India.
            </address>

                    </li>

                </ul>

            </div>
        </div>

        <div class="footer-bottom">
            <p class="copyright">
                &copy; 2024 <a href="#" class="copyright-link">thriceteam</a>.All Right Reserved
            </p>
        </div>

    </footer>





    <!-- 
    - #GO TO TOP
  -->

    <a href="#top" class="go-top  active" aria-label="Go To Top" data-go-top>
        <ion-icon name="arrow-up-outline"></ion-icon>
    </a>





    <!-- 
    - custom js link
  -->
    <script src="./assets/js/script.js"></script>

    <!-- 
    - ionicon link
  -->
    <script type="module" src="https://unpkg.com/ionicons@5.5.2/dist/ionicons/ionicons.esm.js"></script>
    <script nomodule src="https://unpkg.com/ionicons@5.5.2/dist/ionicons/ionicons.js"></script>

</body>
</html>



<style>
:root {
--st-patricks-blue: hsl(236, 57%, 28%);
--amaranth-purple: hsl(335, 88%, 38%);
--royal-blue-dark: hsl(231, 68%, 21%);
--chrome-yellow: hsl(39, 100%, 52%);
--space-cadet-1: hsl(230, 41%, 25%);
--space-cadet-2: hsl(230, 59%, 16%);
--winter-sky_50: hsla(335, 87%, 53%, 0.5);
--purple-navy: hsl(236, 26%, 43%);
--ksu-purple: hsl(275, 54%, 33%);
--winter-sky: hsl(335, 87%, 53%);
--razzmatazz: hsl(335, 87%, 51%);
--platinum: hsl(0, 0%, 90%);
--black_70: hsla(0, 0%, 0%, 0.7);
--rajah: hsl(29, 99%, 67%);
--white: hsl(0, 0%, 100%);
--gradient-1: linear-gradient(90deg,var(--royal-blue-dark) 0,var(--ksu-purple) 51%,var(--royal-blue-dark));
--gradient-2: linear-gradient(90deg,var(--razzmatazz) ,var(--rajah));
--ff-source-sans-pro: 'Source Sans Pro', sans-serif;
--ff-poppins: 'Poppins', sans-serif;
--fs-1: 4.2rem;
--fs-2: 3.8rem;
--fs-3: 3.2rem;
--fs-4: 2.5rem;
--fs-5: 2.4rem;
--fs-6: 2rem;
--fs-7: 1.8rem;
--fs-8: 1.5rem;
--fw-500: 500;
--fw-600: 600;
--fw-700: 700;
--radius-4: 4px;
--radius-12: 12px;
--transition-1: 0.15s ease;
--transition-2: 0.35s ease;
--cubic-in: cubic-bezier(0.51, 0.03, 0.64, 0.28);
--cubic-out: cubic-bezier(0.33, 0.85, 0.56, 1.02);
--shadow: 0 5px 20px 1px hsla(220, 63%, 33%, 0.1);

}
*,
*::before,
*::after {
margin: 0;
padding: 0;
box-sizing: border-box;
}
li { list-style: none; }
a { text-decoration: none; }
a,
img,
span,
input,
button,
ion-icon { display: block; }
button,
input {
background: none;
border: none;
font: inherit;
}
button { cursor: pointer; }
input { width: 100%; }
ion-icon { pointer-events: none; }
img { height: auto; }
address { font-style: normal; }
html {
font-family: var(--ff-poppins);
font-size: 10px;
scroll-behavior: smooth;
}
body {
background-color: var(--white);
color: var(--purple-navy);
font-size: 1.6rem;
}
::-webkit-scrollbar { width: 10px; }
::-webkit-scrollbar-track { background-color: hsl(0, 0%, 95%); }
::-webkit-scrollbar-thumb { background-color: hsl(0, 0%, 80%); }
::-webkit-scrollbar-thumb:hover { background-color: hsl(0, 0%, 70%); }
.container { padding-inline: 15px; }
.h2,
.h3 { font-family: var(--ff-source-sans-pro); }
.btn {
background-image: var(--gradient-2);
background-size: 200%;
color: var(--white);
padding: 12px 35px;
font-size: var(--fs-8);
font-weight: var(--fw-500);
border-radius: 0 25px;
transition: var(--transition-2);
}
.btn:is(:hover, :focus) { background-position: right; }
.w-100 { width: 100%; }
.banner-animation { animation: waveAnim 3s linear infinite alternate; }
@keyframes waveAnim {
0% { transform: translate(0, 0) rotate(1); }
100% { transform: translate(2px, 2px) rotate(1deg); }
}
.section { padding-block: var(--section-padding); }
.section-title {
color: var(--st-patricks-blue);
font-size: var(--fs-3);
margin-block-end: 60px;
max-width: max-content;
margin-inline: auto;
}
.underline { position: relative; }
.underline::before {
content: "";
position: absolute;
bottom: -20px;
left: 50%;
transform: translateX(-50%);
width: 70%;
height: 6px;
background-image: var(--gradient-2);
border-radius: 10px;
}
:is(.service-card, .features-card) .title {
color: var(--st-patricks-blue);
font-size: var(--fs-4);
font-weight: var(--fw-700);
}
:is(.service-card, .features-card, .blog-card) .text { font-size: var(--fs-8); }
.img-cover {
width: 100%;
height: 100%;
object-fit: cover;
}
.header .btn { display: none; }
.header {
--color: var(--white);
position: absolute;
top: 0;
left: 0;
width: 100%;
padding-block: 14px;
z-index: 4;
transition: var(--transition-1);
}
.header.active {
--color: var(--st-patricks-blue);
position: fixed;
background-color: var(--white);
box-shadow: 0 2px 30px hsla(0, 0%, 0%, 0.1);
}
.header .container {
display: flex;
justify-content: space-between;
align-items: center;
gap: 30px;
}
.logo {
color: var(--color);
font-family: var(--ff-source-sans-pro);
font-size: var(--fs-3);
}
.nav-open-btn {
color: var(--color);
font-size: 32px;
padding: 4px;
}
.navbar {
background-color: var(--white);
position: fixed;
top: 0;
left: -280px;
width: 100%;
max-width: 280px;
min-height: 100%;
padding: 20px;
visibility: hidden;
z-index: 2;
transition: 0.25s var(--cubic-in);
}
.navbar.active {
transform: translateX(280px);
visibility: visible;
transition: 0.5s var(--cubic-out);
}
.navbar-top {
display: flex;
justify-content: space-between;
align-items: center;
padding-block: 10px 30px;
}
.navbar-top .logo {
color: var(--st-patricks-blue);
font-size: 4.2rem;
font-weight: var(--fw-700);
}
.nav-close-btn {
color: var(--space-cadet-1);
font-size: 2.8rem;
padding: 4px;
}
.navbar-item:not(:last-child) { border-bottom: 1px solid var(--platinum); }
.navbar-link {
color: var(--space-cadet-1);
font-size: var(--fs-8);
font-weight: var(--fw-600);
padding-block: 12px;
}
.overlay {
position: fixed;
inset: 0;
background-color: var(--black_70);
z-index: 1;
opacity: 0;
pointer-events: none;
transition: var(--transition-2);
}
.overlay.active {
opacity: 1;
pointer-events: all;
}
.hero {
background-image: url("../images/hero-bg-bottom.png"),
                  url("https://coolbackgrounds.io/images/backgrounds/index/compute-ea4c57a4.png"),
                  var(--gradient-1);
background-repeat: no-repeat, no-repeat, no-repeat;
background-position: -280px bottom, center, center;
background-size: auto, cover, auto;
padding-block-start: 120px;
padding-block-end: var(--section-padding);
}
.hero-content { margin-block-end: 50px; }
.hero-subtitle {
color: var(--chrome-yellow);
font-family: var(--ff-source-sans-pro);
font-size: var(--fs-7);
margin-block-end: 15px;
}
.hero-title {
color: var(--white);
font-size: var(--fs-1);
margin-block-end: 20px;
}
.hero-text {
color: var(--white);
font-size: var(--fs-8);
margin-block-end: 30px;
}
.about-banner { margin-block-end: 30px; }
.about .section-title { margin-inline: 0; }
.about .underline::before {
left: 0;
transform: translateX(0);
}
.about-text {
font-size: var(--fs-8);
margin-block-end: 20px;
}
.stats-list {
display: grid;
gap: 30px;
}
.stats-card {
text-align: center;
padding: 15px;
box-shadow: var(--shadow);
border-radius: var(--radius-12);
}
.stats-title {
color: var(--st-patricks-blue);
font-size: var(--fs-2);
font-weight: var(--fw-700);
}
.stats-text { font-size: var(--fs-8); }
.service-list {
display: grid;
gap: 30px;
}
.service-card {
padding: 30px;
box-shadow: var(--shadow);
border-radius: var(--radius-12);
}

.service-card .card-icon {
background-image: url("../images/service-banner-pattern.png");
background-repeat: no-repeat;
background-size: contain;
background-color: hsla(335, 87%, 53%, 0.12);
aspect-ratio: 1 / 1;
max-width: 165px;
display: grid;
place-content: center;
margin-inline: auto;
transition: var(--transition-1);
}

.service-card:hover .card-icon { background-color: var(--winter-sky); }

.service-card .card-icon ion-icon {
font-size: 5rem;
color: var(--winter-sky);
--ionicon-stroke-width: 20px;
transition: var(--transition-1);
}

.service-card:hover .card-icon ion-icon { color: var(--white); }

.service-card .title {
text-align: center;
margin-block-end: 15px;
}

.service-card .text {
text-align: center;
margin-block-end: 20px;
}

.service-card .card-btn {
margin-inline: auto;
padding: 15px;
border: 1px solid var(--winter-sky);
border-radius: 50%;
color: var(--winter-sky);
transition: var(--transition-1);
}

.service-card .card-btn:is(:hover, :focus) {
color: var(--white);
background-color: var(--winter-sky);
}

.features-list > li:first-child { margin-block-end: 30px; }

.features-card {
display: flex;
align-items: flex-start;
gap: 20px;
}

.features-card .icon {
background-image: var(--gradient-1);
background-size: 200%;
color: var(--white);
min-width: max-content;
max-width: max-content;
font-size: 36px;
padding: 22px;
border-radius: 50%;
}

.features-card .icon ion-icon { --ionicon-stroke-width: 20px; }

.features-card .title { margin-block-end: 10px; }

.features-banner { margin-block: 40px; }

.features-banner > img {
max-width: max-content;
margin-inline: auto;
}

.blog { padding-block-end: 120px; }

.blog-list {
display: grid;
gap: 30px;
}

.blog-card {
padding: 20px;
box-shadow: var(--shadow);
border-radius: var(--radius-12);
}

.blog-card .banner {
border-radius: var(--radius-12);
overflow: hidden;
margin-block-end: 15px;
}

.blog-card .banner img { transition: var(--transition-2); }

.blog-card .banner a:is(:hover, :focus) img { transform: scale(1.1); }

.blog-card .title {
color: var(--st-patricks-blue);
font-size: var(--fs-6);
line-height: 1.2;
margin-block-end: 15px;
}

.blog-card .title > a { color: inherit; }

.blog-card .title > a:is(:hover, :focus) { color: var(--razzmatazz); }

.blog-card .text { margin-block-end: 15px; }

.blog-card .meta {
display: flex;
justify-content: space-between;
align-items: center;
gap: 15px;
font-size: var(--fs-8);
color: var(--purple-navy);
font-weight: var(--fw-500);
padding-block-end: 10px;
}

.blog-card .meta ion-icon {
color: var(--winter-sky);
font-size: 22px;
--ionicon-stroke-width: 35px;
}

.publish-date,
.comment {
display: flex;
align-items: center;
gap: 8px;
}

.comment {
color: inherit;
margin-inline-start: auto;
}


.footer { font-size: var(--fs-8); }

.footer a { color: inherit; }

.footer-top {
background-image: url("https://coolbackgrounds.io/images/backgrounds/index/compute-ea4c57a4.png"), var(--gradient-1);
background-repeat: no-repeat;
background-size: auto, 200%;
background-position: center, center;
color: var(--white);
}

.footer-brand { margin-block-end: 30px; }

.footer-brand .logo {
font-weight: var(--fw-700);
margin-block-end: 15px;
}

.footer-brand .text {
font-size: var(--fs-8);
margin-block-end: 20px;
}

.social-list {
display: flex;
justify-content: flex-start;
align-items: center;
gap: 10px;
}

.footer-top .social-link {
background-color: var(--white);
color: var(--winter-sky);
font-size: 18px;
padding: 8px;
border-radius: 50%;
}

.footer-top .social-link:is(:hover, :focus) {
background-image: var(--gradient-2);
color: var(--white);
}

.footer-list:not(:last-child) { margin-block-end: 25px; }

.footer-list-title {
font-family: var(--ff-source-sans-pro);
font-size: var(--fs-5);
font-weight: var(--fw-700);
margin-block-end: 15px;
}

.footer-link { padding-block: 5px; }

:is(.footer-link, .footer-item-link):not(address):is(:hover, :focus) { text-decoration: underline; }

.footer-item {
display: flex;
justify-content: flex-start;
align-items: center;
gap: 10px;
padding-block: 10px;
}

.footer-item-icon {
background-image: var(--gradient-2);
padding: 13px;
border-radius: 50%;
}

.footer-bottom {
background-color: var(--space-cadet-2);
padding: 20px;
text-align: center;
color: var(--white);
}

.copyright-link {
display: inline-block;
text-decoration: underline;
}

.copyright-link:is(:hover, :focus) { text-decoration: none; }


.go-top {
position: fixed;
bottom: 0;
right: 15px;
background-color: var(--winter-sky);
color: var(--white);
font-size: 2rem;
padding: 14px;
border-radius: var(--radius-4);
box-shadow: -3px 3px 15px var(--winter-sky_50);
z-index: 2;
visibility: hidden;
opacity: 0;
transition: var(--transition-1);
}

.go-top.active {
visibility: visible;
opacity: 1;
transform: translateY(-15px);
}

@media (min-width: 550px) {


.container {
  max-width: 550px;
  margin-inline: auto;
}

.section-title { --fs-3: 3.6rem; }

.header .btn {
  display: flex;
  align-items: center;
  gap: 5px;
  margin-inline-start: auto;
}


.stats-list { grid-template-columns: repeat(3, 1fr); }

.blog-card {
  display: grid;
  grid-template-columns: 0.75fr 1fr;
  gap: 20px;
  padding: 30px;
}

.blog-card .banner { margin-block-end: 0; }

.blog-card .banner a { height: 100%; }

.footer-brand,
.footer-list:not(:last-child) { margin-block-end: 0; }

.footer-top .container {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 30px 50px;
}

}

@media (min-width: 768px) {

.container { max-width: 720px; }


.hero {
  min-height: 600px;
  display: grid;
  place-items: center;
}

.hero-content { margin-block-end: 0; }

.hero .container {
  display: grid;
  grid-template-columns: 1fr 1fr;
  align-items: center;
  gap: 30px;
}

.service-list { grid-template-columns: 1fr 1fr; }


.features-list > li:first-child { margin-block-end: 0; }

.features-list {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 25px;
}


.footer-top .container { grid-template-columns: repeat(3, 1fr); }

}


@media (min-width: 992px) {

:root {

  --fs-1: 5.4rem;

}

.container { max-width: 950px; }


.header { padding-block: 20px; }

.overlay,
.nav-open-btn,
.navbar-top { display: none; }

.navbar,
.navbar.active {
  all: unset;
  margin-inline-start: auto;
}

.header .btn { margin-inline-start: 0; }

.navbar-list {
  display: flex;
  gap: 25px;
}

.navbar-item:not(:last-child) { border-bottom: none; }

.navbar-link { color: var(--color); }



.hero { min-height: 700px; }



.about .container {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 30px;
}



.service-list { grid-template-columns: repeat(3, 1fr); }


.features-list { grid-template-columns: 1fr; }

.features .container {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 30px;
}

.features .section-title { grid-column: 1 / 4; }

.features-banner {
  margin-block: 0;
  display: grid;
  place-items: center;
}



.footer-top .container { grid-template-columns: repeat(4, 1fr); }

.footer-brand { grid-column: 1 / 5; }

.footer-brand .text { max-width: 45ch; }

}
 

@media (min-width: 1200px) {

.container { max-width: 1200px; }

.section-title { --fs-3: 4.6rem; }



.hero { min-height: 800px; }


.blog-list { grid-template-columns: 1fr 1fr; }

.blog-card { height: 100%; }

.blog-card .content {
  display: flex;
  flex-direction: column;
  justify-content: space-between;
}



.footer-top .container { grid-template-columns: 1fr 0.5fr 0.7fr 0.5fr 1fr; }

.footer-brand { grid-column: auto; }

}
</style>


<script>
    'use strict';



/**
 * navbar toggle
 */

const navOpenBtn = document.querySelector("[data-nav-open-btn]");
const navbar = document.querySelector("[data-navbar]");
const navCloseBtn = document.querySelector("[data-nav-close-btn]");
const overlay = document.querySelector("[data-overlay]");

const elemArr = [navCloseBtn, overlay, navOpenBtn];

for (let i = 0; i < elemArr.length; i++) {
  elemArr[i].addEventListener("click", function () {
    navbar.classList.toggle("active");
    overlay.classList.toggle("active");
  });
}

/**
 * toggle navbar & overlay when click any navbar-link
 */

const navbarLinks = document.querySelectorAll("[data-navbar-link]");

for (let i = 0; i < navbarLinks.length; i++) {
  navbarLinks[i].addEventListener("click", function () {
    navbar.classList.toggle("active");
    overlay.classList.toggle("active");
  });
}
/**
 * header & go-top-btn active
 * when window scroll down to 400px
 */

const header = document.querySelector("[data-header]");
const goTopBtn = document.querySelector("[data-go-top]");

window.addEventListener("scroll", function () {
  if (window.scrollY >= 400) {
    header.classList.add("active");
    goTopBtn.classList.add("active");
  } else {
    header.classList.remove("active");
    goTopBtn.classList.remove("active");
  }
});
</script>
