<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>3D Portfolio Website using HTML CSS and Javascript  | Prerna </title>
    <!-- <link rel="stylesheet" href="style.css">
    box-icons -->
    <link href='https://unpkg.com/boxicons@2.1.4/css/boxicons.min.css' rel='stylesheet'>
</head>
<body>
    <div class="wrapper">
        <div class="cover cover-left"></div>
        <div class="cover cover-right"></div>

        <div class="book">
        <!--profile page-->
            <div class="book-page page-left">
                <div class="profile-page">
                    <img src="profile-photo.png" alt="pp">
                    <h1>Prerna Deshmane</h1>
                    <h3>Web Developer</h3>

                    <div class="social-media">
                        <a href="#"><i class='bx bxl-facebook'></i></a>
                        <a href="#"><i class='bx bxl-twitter'></i></a>
                        <a href="#"><i class='bx bxl-linkedin'></i></a>
                        <a href="#"><i class='bx bxl-instagram' ></i></a>
                    </div>

                    <p>Hi, I'm Prerna Deshmane, a web developer. Lorem ipsum dolor, sit amet consectetur adipisicing elit. Nemo quisquam earum ipsa tempore expedita.</p>

                    <div class="btn-box">
                        <a href="resume.pdf" class="btn">Download CV</a>
                        <a href="#" class="btn contact-me">Contact Me</a>
                    </div>
                </div>
            </div>

            <!--page 1  &  2-->
            <div class="book-page page-right turn " id="turn-1">
                <!--page 1 (skill section)-->
                <div class="page-front">
                    <h1 class="title">Skills</h1>
                    <div class="skills-box">
                        <div class="skills-content">
                            <h3>Front-End</h3>
                            <div class="content">
                                <span><i class='bx bxl-html5'></i>HTML</span>
                                <span><i class='bx bxl-css3' ></i>CSS</span>
                                <span><i class='bx bxl-javascript' ></i>JS</span>
                                <span><i class='bx bxl-angular' ></i>Angular</span>
                                <span><i class='bx bxl-react' ></i>React</span>
                                <span><i class='bx bxl-bootstrap' ></i>Bootstrap</span>
                            </div>
                        </div>

                        <div class="skills-content">
                            <h3>Back-End</h3>
                            <div class="content">
                                <span><i class='bx bxl-python' ></i>Python</span>
                                <span><i class='bx bxl-java' ></i>Java</span>
                                <span><i class='bx bxl-php' ></i>PHP</span>
                                <span><i class='bx bxl-nodejs' ></i>Node</span>
                            </div>
                        </div>

                        <div class="skills-content">
                            <h3>UI/UX Design</h3>
                            <div class="content">
                                <span><i class='bx bxl-figma' ></i>Figma</span>
                            </div>
                        </div>
                    </div>
                <span class="number-page">1</span>

                <!-- next-btn -->
                 <span class="nextprev-btn" data-page="turn-1">
                    <i class='bx bx-chevron-right' ></i>
                 </span>
                </div>
                <div class="page-back">
                    <h1 class="title">Latest Projects</h1>
                    <div class="portfolio-box">
                        <div class="img-box">
                            <img src="e-com1.jpg" alt="  ">
                        </div>
                        
                        <div class="info-box">
                            <div class="info-title">
                                <h3>Name : ShopEase </h3>
                                <a href="#">Live Preview<i class='bx bx-link-external'></i></a>
                            </div>
                        </div>
                        
                            <h3>Tech used:</h3>
                            <p>An e-commerce website using html, css and js with MySQL to handle the backend and database. </p>
    
                        <div class="btn-box">
                            <a href="#" class="btn">Source Code</a>
                            <a href="#" class="btn">More Projects</a>
                        </div>
                    </div>
                 <span class="number-page">2</span>

                 <!-- next-btn -->
                 <span class="nextprev-btn-back" data-page="turn-1">
                    <i class='bx bx-chevron-left' ></i>
                 </span>  
                </div>
            </div> 
            
            <div class="book-page page-right turn " id="turn-2">
                <!-- page 3(my resume) -->
                <div class="page-front">
                    <h1 class="title">My Resume</h1>
                    <div class="heading">
                        <h2>Education</h2>
                        <div class="workedu-box">
                            <div class="workedu-content">
                                <span class="year"><i class='bx bxs-calendar' ></i>2018-2019</span>
                                <h4>SSC - State Board</h4>
                                <p>R.I.K.P. Mohol.</p>
                                <p>Percentage : 91 %</p>
                            </div>

                            <div class="workedu-content">
                                <span class="year"><i class='bx bxs-calendar' ></i>2020-2021</span>
                                <h4>HSC - State Board</h4>
                                <p>Netaji jr. College, Mohol.</p>
                                <p>Percentage : 91 %</p>
                            </div>

                            <div class="workedu-content">
                                <span class="year"><i class='bx bxs-calendar' ></i>2024-2025</span>
                                <h4>B.Tech (CSE) - Solapur University.</h4>
                                <p>NBN Sinhgad College Of Engineering, Solapur.</p>
                                <p>CGPA : 9.55</p>
                            </div>

                        </div>
                    </div>

                    <div class="heading">
                        <h2>Co-curricular Activities</h2>
                        <div class="co-box">
                            <div class="co-content">
                                <span class="award"><i class='bx bx-award' ></i>Done 1 Month Android Internship<span> <br>  
                                <span class="award"><i class='bx bxs-trophy' ></i>Ramanujan Ganit Gaurav Award.</span>
                            </div>
                        </div>
                    </div>
                    <a href="resume.pdf" class="link">Download CV</a>
                    <span class="number-page">3</span>

                    <!-- next-btn -->
                    <span class="nextprev-btn" data-page="turn-2">
                        <i class='bx bx-chevron-right' ></i>
                    </span> 
                </div>
               
                
                <!-- page 4 (Contact) -->
                 <div class="page-back">
                    <h1 class="title">Contact Me</h1>
                    <div class="contact-box">
                        <form action="#">
                            <input type="text" class="field" placeholder="Full Name" required>
                            <input type="email" class="field" placeholder="Email Address" required>
                            <textarea name="" id="" cols="30" rows="10" class="field" placeholder="Your Message" required></textarea>
                            <input type="submit" class="btn" value="Send Message">
                        </form>
                        <div class="contact-info">
                            <span class="info"><i class='bx bx-phone '></i> -  9960938827</span><br>
                            <span class="info"><i class='bx bxl-gmail ' ></i> -  dprerana04@gmail.com</span>
                        </div>
                    </div>
                    <a href=""></a>
                    <span class="number-page">4</span>
                    <span class="nextprev-btn-back" data-page="turn-2">
                        <i class='bx bx-chevron-left' ></i>
                     </span>
                     <a href="#" class="back-profile">
                        <p>Profile</p>
                        <i class='bx bxs-user' ></i>
                     </a>
                 </div>
            </div>
        </div>
    </div>
    <script src="script.js"></script>
</body>
</html>
