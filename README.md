# Netflix-Clone
 Source Code for Netflix Clone
 The following is the source code for cloning Netflix.
 It has two parts 1. index.html &
                  2. style.css
 ----------------------------
 index.html
 ----------------------------
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Netflix India – Watch TV Shows Online, Watch Movies Online</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>

    <div class="main">
        <nav>
            <span><img width="53" src="assets/Images/logo.svg" alt=""></span>
            <div>
                <button class="btn">English</button>
                <button class="btn btn-red-sm">Sign In</button>
            </div>
        </nav>
        <div class="box">
        </div>
        <div class="hero">
            <span>Enjoy big movies, hit series and more from ₹ 149.</span>
            <span>Join today. Cancel anytime.</span>
            <span>Ready to watch? Enter your email to create or restart your membership.</span>
            <div class="hero-buttons">
                <input type="text" placeholder="Email Address">
                <button class="btn btn-red">Get Started &gt;</button>
            </div>
        </div>

        <div class="separation"></div>

    </div>

    <section class="first">
        <div>
            <span>Enjoy on your TV</span>
            <span>Watch on smart TVs, PlayStation, Xbox, Chromecast, Apple TV, Blu-ray players and more.</span>
        </div>

        <div class="secImg">
            <img src="https://assets.nflxext.com/ffe/siteui/acquisition/ourStory/fuji/desktop/tv.png" alt="">
            <video src="https://assets.nflxext.com/ffe/siteui/acquisition/ourStory/fuji/desktop/video-tv-in-0819.m4v"
                autoplay loop muted></video>
        </div>
    </section>
    <div class="separation"></div>

    <section class="first second">

        <div class="secImg">
            <img src="https://assets.nflxext.com/ffe/siteui/acquisition/ourStory/fuji/desktop/mobile-0819.jpg" alt="">

        </div>
        <div>
            <span>Download your shows to watch offline</span>
            <span>Save your favourites easily and always have something to watch.</span>
        </div>
    </section>

    <div class="separation"></div>
    <section class="first third">
        <div>
            <span>Watch everywhere</span>
            <span>Stream unlimited movies and TV shows on your phone, tablet, laptop, and TV.</span>
        </div>

        <div class="secImg">
            <img src="https://assets.nflxext.com/ffe/siteui/acquisition/ourStory/fuji/desktop/tv.png" alt="">
            <video src="https://assets.nflxext.com/ffe/siteui/acquisition/ourStory/fuji/desktop/video-devices-in.m4v"
                autoplay loop muted></video>
        </div>
    </section>
    <div class="separation"></div>


    <section class="first second">

        <div class="secImg">
            <img src="https://occ-0-2849-3646.1.nflxso.net/dnm/api/v6/19OhWN2dO19C9txTON9tvTFtefw/AAAABVr8nYuAg0xDpXDv0VI9HUoH7r2aGp4TKRCsKNQrMwxzTtr-NlwOHeS8bCI2oeZddmu3nMYr3j9MjYhHyjBASb1FaOGYZNYvPBCL.png?r=54d"
                alt="">

        </div>
        <div>
            <span>Create profiles for kids</span>
            <span>Send children on adventures with their favourite characters in a space made just for them—free with
                your membership.</span>
        </div>
    </section>

    <div class="separation"></div>

    <section class="faq">
        <h2>Frequently Asked Questions</h2>
        <div class="faqbox">
            <span>What is NetFlix</span>
            <svg width="24" height="24" viewBox="0 0 24 24" fill="white" xmlns="http://www.w3.org/2000/svg">
                <path d="M12 4V20" stroke="#141B34" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round" />
                <path d="M4 12H20" stroke="#141B34" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round" />
            </svg>

        </div>
        <div class="faqbox">
            <span>How much does Netflix cost?</span>
            <svg width="24" height="24" viewBox="0 0 24 24" fill="white" xmlns="http://www.w3.org/2000/svg">
                <path d="M12 4V20" stroke="#141B34" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round" />
                <path d="M4 12H20" stroke="#141B34" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round" />
            </svg>

        </div>
        <div class="faqbox">
            <span>What can I watch on Netflix?</span>
            <svg width="24" height="24" viewBox="0 0 24 24" fill="white" xmlns="http://www.w3.org/2000/svg">
                <path d="M12 4V20" stroke="#141B34" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round" />
                <path d="M4 12H20" stroke="#141B34" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round" />
            </svg>

        </div>
        <div class="faqbox">
            <span>Where can I watch?</span>
            <svg width="24" height="24" viewBox="0 0 24 24" fill="white" xmlns="http://www.w3.org/2000/svg">
                <path d="M12 4V20" stroke="#141B34" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round" />
                <path d="M4 12H20" stroke="#141B34" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round" />
            </svg>

        </div>
    </section>
    <div class="separation"></div>

    <footer>
        <div class="questions">
            Questions? Call 000-800-919-1694
        </div>
        <div class="footer">
            <div class="footer-item"> 
                <a href="faq">Investor Relations</a>
                <a href="faq">Jobs</a>
                <a href="faq">Ways to Watch</a>
                <a href="faq">Terms of Use</a>
            </div>

            <div class="footer-item"> 
                <a href="faq">Help Centre</a>
                <a href="faq">Account</a>
                <a href="faq">Speed Test</a>
                <a href="faq">Legal Notices</a>
            </div>
            <div class="footer-item">
                <a href="faq">Media Centre</a>
                <a href="faq">Privacy</a>
                <a href="faq">Cookie Preferences</a> 
                <a href="faq">Corporate</a>
            </div>

            <div class="footer-item">
                <a href="faq">Contact Us</a>
                <a href="faq">Speed Test</a> 
                <a href="faq">Legal Notices</a> 
                <a href="faq">Only on Netflix</a>
            </div>
        </div>
    </footer>
</body>

</html>

--------------------------------------
style.css
--------------------------------------
@import url('https://fonts.googleapis.com/css2?family=Martel+Sans:wght@600&family=Poppins:wght@300;400;700&display=swap');

* {
    padding: 0;
    margin: 0;
    font-family: 'Poppins', sans-serif;
}

body {
    background-color: black;
}

.main {
    background-image: url("assets/images/bg.jpg");
    background-position: center center;
    background-size: max(1200px, 100vw);
    background-repeat: no-repeat;
    height: 644px;
    position: relative;
}

.main .box {
    height: 644px;
    width: 100%;
    opacity: 0.69;
    position: absolute;
    top: 0;
    background-color: black;
}

nav {
    max-width: 60vw;
    justify-content: space-between;
    margin: auto;
    display: flex;
    align-items: center;
    height: 100px;
}

nav img {
    color: red;
    width: 130px;
    position: relative;
    z-index: 10;
}

nav button {
    position: relative;
    z-index: 10;
}

.hero {
    font-family: 'Martel Sans', sans-serif;
    height: calc(100% - 100px);
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
    color: white;
    position: relative;
    gap: 23px;
    padding: 0 30px;
}

.hero> :nth-child(1) {
    font-family: 'Poppins', sans-serif;
    font-weight: bolder;
    font-size: 48px;
    text-align: center;
}

.hero> :nth-child(2) {
    font-weight: 400;
    font-size: 24px;
    text-align: center;
}

.hero> :nth-child(3) {
    font-weight: 400;
    font-size: 20px;
    text-align: center;
}

.separation {
    height: 7px;
    background-color: rgb(46, 44, 44);
    position: relative;
    z-index: 20;
}

.btn {
    padding: 3px 8px;
    font-weight: 400;
    color: white;
    background-color: rgba(248, 243, 243, 0.021);
    border-radius: 4px;
    border: 1px solid white;
    cursor: pointer;

}

.btn-red {
    background-color: red;
    color: white;
    padding: 3px 24px;
    font-size: 20px;
    border-radius: 4px;
    font-weight: 400;
}

.btn-red-sm {
    background-color: red;
    color: white;
}

.hero-buttons {
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 16px;
}

.main input {
    padding: 7px 101px 8px 14px;
    color: white;
    font-size: 12px;
    border-radius: 4px;
    background-color: rgba(23, 23, 23, 0.7);
    border: 1px solid rgba(246, 238, 238, 0.5);
}

.first {
    display: flex;
    justify-content: center;
    max-width: 70vw;
    margin: auto;
    color: white;
    justify-content: center;
    align-items: center;
}



.secImg {
    position: relative;
}

.secImg img {
    width: 555px;
    position: relative;
    z-index: 10;
}

.secImg video {
    position: absolute;
    top: 51px;
    right: 0;
    width: 555px;
}

section.first>div {
    display: flex;
    flex-direction: column;
    padding: 34px 0;
}

section.first>div :nth-child(1) {
    font-size: 48px;
    font-weight: bolder;
}


section.first>div :nth-child(2) {
    font-size: 24px;

}


.faq h2 {
    text-align: center;
    font-size: 48px;
}

.faq {
    background: black;
    color: white;
    padding: 34px;
}

.faqbox:hover {
    background-color: #414141;
    color: white;
}

.faqbox svg {
    filter: invert(1);
}

.faqbox {
    transition: all 1s ease-out;
    font-size: 24px;
    display: flex;
    justify-content: space-between;
    background-color: #2d2d2d;
    padding: 24px;
    max-width: 60vw;
    margin: 34px auto;
    cursor: pointer;
}

footer {
    color: white;
    max-width: 60vw;
    margin: auto;
    padding: 60px;
}

footer .questions {
    padding: 34px 0;
}


.footer {
    display: grid;
    grid-template-columns: 1fr 1fr 1fr 1fr;
    color: white;
}



@media screen and (max-width: 1300px) {

    nav{
        max-width: 90vw;
    }

    .first {
        flex-wrap: wrap;
    }

    .secImg img {
        width: 305px;
    }

    .secImg video {
        width: 305px;
    }

    .hero> :nth-child(1) {
        font-size: 32px;
    }

    .hero> :nth-child(2) {
        font-size: 18px;
    }

    .hero> :nth-child(3) {
        font-size: 18px;
    }

    .hero-buttons {
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
        gap: 16px;
    }

    .faq h2 {
        text-align: center;
        font-size: 32px;
    }

    footer {
        max-width: 90vw;
        padding: 75px 0;
    }

    .footer-item{
        align-items: center;
    }
 

}

@media screen and (max-width: 1300px) {

    .footer {
        display: grid;
        grid-template-columns: 1fr 1fr;
        gap: 25px;
    }
}


.footer a {
    font-size: 14px;
    color: white;
}

.footer-item {
    display: flex;
    flex-direction: column;
    gap: 23px;
}

