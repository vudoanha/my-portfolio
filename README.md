# my-portfolio
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML CSS</title>
    <link 
    rel="stylesheet" 
    href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.6.0/css/all.min.css" 
    integrity="sha512-Kc323vGBEqzTmouAECnVceyQqyqdsSiqLQISBL29aUW4U/M7pSPA/gEUZQqv1cwx4OnYxTxve5UMg5GT6L4JJg==" 
    crossorigin="anonymous" 
    referrerpolicy="no-referrer" 
    />
    <link rel="stylesheet" href="./assets/css/style.css"/>
</head>
<body>
    <header>
        <div class="intro">
            <h1>Hello, I'm Vu Doan Ha</h1>
            <p>Web Developer | Designer | Creator</p>
            <a href="#projects" class="button">View My Work</a>
        </div>
        <img src="./assets/img/your-photo.jpg.jpg" alt="Your Photo" class="profile-photo">
    </header>
    <!--Home Section-->
    <section id="home">
    <h2>Welcome to  </h2>

    <!--Video Introduction-->
    <div class="video-intro">
        <span>Video introduce about me</span>
        <blockquote 
        class="tiktok-embed" 
        cite="https://www.tiktok.com/@vudoanha/video/7011156749877103899" 
        data-video-id="7011156749877103899" 
        style="max-width: 605px;min-width: 325px;" > 
        <section> 
            <a target="_blank" title="@vudoanha" href="https://www.tiktok.com/@vudoanha?refer=embed">@vudoanha</a> 
            <a title="utt" target="_blank" href="https://www.tiktok.com/tag/utt?refer=embed">#utt</a> 
            <a title="sinhvienutt" target="_blank" href="https://www.tiktok.com/tag/sinhvienutt?refer=embed">#sinhvienutt</a> 
        </section> 
        </blockquote> <script async src="https://www.tiktok.com/embed.js"></script>
    </div>

    <!--Companies Worked-->
    <div class="companies">
        <h3>Company has worked</h3>
        <ul>
            <li>Udonjelly - Designer</li>
        </ul>
    </div>

    <!--Schools learned-->
    <div class="schools">
        <h3>Schools have learned</h3>
        <ul>
            <li>Quang Trung - Đống Đa highschool (2018-2021)</li>
            <li>University Of Transport Technology (2021-2025)</li>
        </ul>
    </div>

    <!--Button to Go to Detail-->
    <a href="#about" class="button">Go to About me</a>
    </section>
    <!--About Section: Self-introduction-->
    <section id="about">
        <h2>About Me</h2>   
        <p class="introduce">Hello! I'm Ha, a passionate web developer with a knack for crafting engaging and user-friendly digital experiences.</p>
    </section>

    <!--Projects-->
    <section id="projects">
        <h2>Projects</h2>
        <div class="project-list">
            <div class="project-item">
                <h3>Decision to go to the movies based on the weather forecast <br>(20/03/2024 - 02/05/2024)</h3><br>
                <p><strong>Project Description: </strong>Develop a system that uses weather data to make decisions on whether or not to go to the movies.</p><br>
                <div class="technologies">
                    <h4>Technologies used:</h4>
                        <div>Python</div>
                        <div>Qt Designer</div>
                        <div>Pandas</div>
                        <div>Scikit Learn: decision tree</div>
                </div>
            </div>
        </div>
    </section>

    <!--Skills-->
    <section id="skills">
        <div class="skills">
            <h2>Skills</h2>
            <ul class="each-skill">
                <li>HTML, CSS, JavaScript</li>
                <li>React, Angular, Vue</li>
                <li>Problem Solving and Critical Thinking</li>
            </ul>
        </div>
    </section>
    <!--Experiences-->
    <section id="experience">
        <h2>Experiences</h2>
        <div class="experience-list">
            <div class="experience-item">
                <h3><strong>NO EXPERIENCE</strong></h3>
            </div>
        </div>
    </section>
    <footer>
        <div class="social-media">
        <a href="https://www.facebook.com/udonjelly"
            class="facebook-link"
            target="_blank" 
            rel="noopener noreferrer">
            <i class="fa-brands fa-facebook-f"></i>Facebook <br>
        </a> <a href="https://www.tiktok.com/@vudoanha?is_from_webapp=1&sender_device=pc"
            class="tiktok-link"
            target="_blank" 
            rel="noopener noreferrer">
            <i class="fab fa-tiktok"></i>TikTok <br>
        </a>
        <span class="gmail"><i class="fa-solid fa-envelope"></i>
            <u>vudoanha10102003@gmail.com</u>
        </span>
        </div>
    </footer>
</body>
</html>
