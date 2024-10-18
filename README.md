
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>One Page Website</title>
    <link rel="stylesheet" href="/CSS/styles.css">
    <link rel="stylesheet" href="/CSS/css/all.css">
    <link rel="stylesheet" href="/CSS/light.css" id="themeStyle">
</head>
<body>
                 <!-- Header Section -->
     <div class="main-pic">
        <div>
            <header>
                <div class="logo">
                    <img src="/Assets/IMG/logo.png" alt="Dance Logo" width="50px" class="logo-img">
                
                <nav>
            <div class="menuList">
                <ul class="main">
                    <li><a href="#">intro</a></li>
                    <li><a href="#">countdown</a></li>
                    <li><a href="#">notes</a></li>
                    <li><a href="#">location</a></li>
                    <li><a href="#">contact</a></li>
                </ul>
        </nav>
        <a href="#" class="call" onclick="document.getElementById('themeStyle').setAttribute('href', '/CSS/dark.css'); 
        document.getElementById('shapeTop').src='/Assets/IMG/shape-top-black-80.png'; 
        document.getElementById('logoBottom').src='/Assets/IMG/shape-top-dark-grey-80.png';
        document.getElementById('shapebottom').src='/Assets/IMG/shape-top-dark-grey-80.png';"><i class="fa-solid fa-moon"></i></a>
    </div>
</div>
        </header>

        <!-- Hero Section -->
<section>
        <div class="imgText">        
            <h5>imomotimi foundation presents</h5>
            <div class="ijaw">
            <h1>imomotimi ijaw </h1> 
            <h1>dance contest 2024</h1>
        </div>
            <button value="submit">Download entry form <i class="fa-solid fa-download"></i></button>
            <p>All duly filled out forms and the entry 
                fees should be brought to the auditions.</p>
        </div>
        <div class="shapeTop">
            <img id="shapeTop" src="../Assets/IMG/shape-top-white-80.png" alt="logo" width="100%">
        </div>
     </div>  
    </section>
              <!-- countdown section -->
               <section>
     <div class="countdown-container" id="countdown">
        <h2>Countdown to Audition</h2>
        <div class="countdown-timer">
            <div class="time-section">
                <span class="time">29</span><hr width="15px">
                <p>Days</p>
            </div>
            <span class="colon">:</span>
            <div class="time-section">
                <span class="time">02</span> <hr width="15px">
                <p>Hours</p>
            </div>
            <span class="colon">:</span>
            <div class="time-section">
                <span class="time">08</span><hr width="15px">
                <p>Minutes</p>
            </div>
            <span class="colon">:</span>
            <div class="time-section">
                <span class="time">06</span><hr width="15px">
                <p>Seconds</p>
            </div>
        </div>
        
        <img id="logoBottom" src="../Assets/IMG/shape-top-grey-80.png" alt="Logo Bottom" class="logoBottom" width="100%">
    </div>
</section>

   
          
        <section>
            <div class="important" id="important">
                <h2>   Important things to note....</h2>
                <div class="detail">
                    <ul class="prize-list" id="importantText">
                        <li><i class="fa fa-money-bill-wave"></i></li>
                        <li><strong>Pricing</strong></li>
                        <li>Audition forms are available for </li>
                        <li> &#8358;1,000 single contestants,</li> 
                        <li>and &#8358;1,500 for a group of five.</li>
                    </ul>
                </div>
                <div class="detail">
                    <ul class="prize-list" id="importantText2">
                        <li><i class="fa fa-trophy"></i></li>
                        <li><strong>Prizes</strong></li>
                        <li><strong>1st Prize: &#8358;</strong>2,000,000</li>
                        <li><strong>2nd Prize: &#8358;</strong>1,000,000</li>
                        <li><strong>3rd Prize: &#8358;</strong>500,000</li>
                    </ul>
                </div>
            </div>
        </section>
        <!-- map -->
        <div>
            <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3975.0515592997285!2d6.318390373439563!3d4.931030995044984!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x106a055be1dcce59%3A0xa6c5b6a97ac6c1a!2sNitro%20Studios!5e0!3m2!1sen!2sng!4v1727795628840!5m2!1sen!2sng" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade" class="map"></iframe>
        </div>
        <div class="bottomGrey"><img src="/Assets/IMG/shape-top-grey-80.png" alt="Shape Bottom" width="100%" id="shapebottom"></div>

        <section>
            <div class="contact-section" id="contact">
                <div class="contact-info">
                    <h2>For More Information:</h2>
                    <p><strong>Hotlines:</strong> 07035973706 & 08108112759</p>
                    <p><strong>Email:</strong> info@ijawdancecontest.ng</p>
                    <p><strong>Audition Location:</strong> Nitro Studio, Tamara Hall, Otiotio Road, Yenegoa, Bayelsa State.</p>
                </div>

                <div class="contact-form">
                    <form action="" method="POST">
                        <div class="form-group">
                            <div class="inputicon">
                        <i class="fas fa-user"></i><input type="text" name="fname" placeholder="Name"></div>
                        <div class="inputicon">
                        <i class="fas fa-phone-volume"></i><input type="tel" name="phone" placeholder="Phone"></div>
                    </div>
                    <div class="form-group">
                        <div class="inputicon">
                        <i class="fas fa-envelope"></i><input type="email" name="email" placeholder="Email" class="email">
                    </div>
                        <div class="inputicon">
                        <i class="fas fa-info-circle"></i><input type="text" name="subject" placeholder="Subject">
                    </div>
                    </di>
                        <i class="fa-solid fa-pencil"></i><textarea name="message" id="message" placeholder="How can we help you? Feel free to get in touch!"></textarea>
                        <button type="submit">Get In Touch</button>
                    </form>
                </div>
            </div>
        </section>
       <section>
        <footer>
            <div class="footerSocial">
                <h3>We are social</h3>
                <div class="socialIcons">
                    <a href="#"><span class="icon-container"><i class="fa-brands fa-facebook-f"></i></span></i></a>
                    <a href="#"><span class="icon-container"><i class="fa-brands fa-x-twitter"></i></span></i></a>
                    <a href="#"><span class="icon-container"><i class="fa-brands fa-instagram"></i></span></i></a>
                    <a href="#"><span class="icon-container"><i class="fa-brands fa-youtube"></i></span></i></a>
                </div>
            </div>
            <p><hr></p>
            <p>&copy; 2024 Imomotimi Foundation. All Rights Reserved.</p>
        </footer>
       </section>
</body>
</html>
