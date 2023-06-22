# Ex-01 To create a web Portfolio CV using HTML CSS
## Aim:-
To create a web Portfolio CV using HTML CSS
## Algorithm:-
### Step 1:
index.html: The main HTML file.
### Step 2:
style.css: The CSS file for styling the portfolio.
### Step 3:
Add content to the portfolio
### Step 4:
Link the CSS file
### Step 5:
Style the portfolio using CSS
### Step 6:
Publish your portfolio
## Program:-
#### Developed By : KIRUPANANDHAN T
#### Register Number : 212221230051
### Index.html
```
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <link rel="stylesheet" href="styles.css">
        <link href='https://cdn.jsdelivr.net/npm/boxicons@2.0.5/css/boxicons.min.css' rel='stylesheet'>

        <title> Portfolio Website</title>
    </head>
    <body>

         <!-- HEADER -->
         <header class="l-header">
            <nav class="nav bd-grid">
                <div>
                    <a href="#" class="nav__logo">Kirupanandhan</a>
                </div>

                <div class="nav__menu" id="nav-menu">
                    <ul class="nav__list">
                        <li class="nav__item"><a href="#home" class="nav__link active">Home</a></li>
                        <li class="nav__item"><a href="#about" class="nav__link">About</a></li>
                        <li class="nav__item"><a href="#skills" class="nav__link">Skills</a></li>
                        <li class="nav__item"><a href="#work" class="nav__link">Work</a></li>
                        <li class="nav__item"><a href="#contact" class="nav__link">Contact</a></li>
                    </ul>
                </div>

                <div class="nav__toggle" id="nav-toggle">
                    <i class='bx bx-menu'></i>
                </div>
            </nav>
        </header>

        <main class="l-main">
            <!--===== HOME =====-->
            <section class="home bd-grid" id="home">
                <div class="home__data">
                    <h1 class="home__title">Hi,<br>I'am <span class="home__title-color">Kirupanandhan</span><br> Web Developer</h1>

                    <a href="i1.html" class="button">CV</a>
                </div>

                <div class="home__social">
                    <a href="" class="home__social-icon"><i class='bx bxl-linkedin'></i></a>
                    <a href="" class="home__social-icon"><i class='bx bxl-behance' ></i></a>
                    <a href="" class="home__social-icon"><i class='bx bxl-github' ></i></a>
                </div>

                <div class="home__img">    
                    <img src="https://img.freepik.com/free-vector/web-design-production-maintenance-websites-web-graphic-interface-design-responsive-website-software-engineering-development-colorful-icon_335657-2699.jpg" alt="">
                </div>
            </section>

            <!--===== ABOUT =====-->
            <section class="about section " id="about">
                <h2 class="section-title">About</h2>

                <div class="about__container bd-grid">
                    <div class="about__img">
                        <img src="https://encrypted-tbn3.gstatic.com/images?q=tbn:ANd9GcTKE5Uyiph8Yan0zBNUNDEBFe2CIK_Ux9YMzCCQaHievM8YZhW1" alt="">
                    </div>
                    
                    <div>
                        <h2 class="about__subtitle">I'am Kirupanandhan</h2>
                        <p class="about__text">As a web developer, I am a skilled professional with a passion for crafting innovative and visually appealing websites. I possess expertise in programming languages such as HTML, CSS, and JavaScript, which allows me to create dynamic and interactive web experiences. I am well-versed in responsive design principles, ensuring that websites adapt seamlessly to different devices and screen sizes.

                         <br><br>   With a strong attention to detail and a problem-solving mindset, I thrive on overcoming challenges and finding creative solutions to meet clients' specific needs. I am experienced in collaborating with designers, content creators, and project managers to bring ideas to life and deliver exceptional websites that exceed expectations.</p>           
                    </div>                                   
                </div>
            </section>

            <!--===== SKILLS =====-->
            <section class="skills section" id="skills">
                <h2 class="section-title">Skills</h2>

                <div class="skills__container bd-grid">          
                    <div>
                        <h2 class="skills__subtitle">Profesional Skills</h2>
                        <p class="skills__text"> my professional skills include proficiency in HTML, CSS, and JavaScript, allowing me to build dynamic and engaging websites. I am experienced in working with frameworks like React and Angular, enabling me to create scalable and interactive web applications. </p>
                        <div class="skills__data">
                            <div class="skills__names">
                                <i class='bx bxl-html5 skills__icon'></i>
                                <span class="skills__name">HTML5</span>
                            </div>
                            <div class="skills__bar skills__html">

                            </div>
                            <div>
                                <span class="skills__percentage">90%</span>
                            </div>
                        </div>
                        <div class="skills__data">
                            <div class="skills__names">
                                <i class='bx bxl-css3 skills__icon'></i>
                                <span class="skills__name">CSS</span>
                            </div>
                            <div class="skills__bar skills__css">
                                
                            </div>
                            <div>
                                <span class="skills__percentage">80%</span>
                            </div>
                        </div>
                        <div class="skills__data">
                            <div class="skills__names">
                                <i class='bx bxl-javascript skills__icon' ></i>
                                <span class="skills__name">JAVASCRIPT</span>
                            </div>
                            <div class="skills__bar skills__js">
                                
                            </div>
                            <div>
                                <span class="skills__percentage">60%</span>
                            </div>
                        </div>
                        <div class="skills__data">
                            <div class="skills__names">
                                <i class='bx bxs-paint skills__icon'></i>
                                <span class="skills__name">PHP</span>
                            </div>
                            <div class="skills__bar skills__ux">
                                
                            </div>
                            <div>
                                <span class="skills__percentage">75%</span>
                            </div>
                        </div>
                    </div>
                    
                    <div>              
                        <img src="https://img.freepik.com/free-vector/tiny-graphic-designer-drawing-with-big-pen-computer-screen-creators-work-creative-woman-working-laptop-flat-vector-illustration-digital-design-concept-banner-landing-web-page_74855-25342.jpg" alt="" class="skills__img">
                    </div>
                </div>
            </section>

            <!--===== WORK =====-->
            <section class="work section" id="work">
                <h2 class="section-title">Work</h2>

                <div class="work__container bd-grid">
                    <div class="work__img">
                        <img src="img/1.jpg" alt="">
                    </div>
                    <div class="work__img">
                        <img src="img/2.jpg" alt="">
                    </div>
                    <div class="work__img">
                        <img src="img/3.jpg" alt="">
                    </div>
                    <div class="work__img">
                        <img src="img/4.jpg" alt="">
                    </div>
                    <div class="work__img">
                        <img src="img/5.jpg" alt="">
                    </div>
                    <div class="work__img">
                        <img src="img/6.jpg" alt="">
                    </div>
                </div>
            </section>

            <!--===== CONTACT =====-->
            <section class="contact section" id="contact">
                <h2 class="section-title">Contact</h2>

                <div class="contact__container bd-grid">
                    <form action="" class="contact__form">
                        <input type="text" placeholder="Name" class="contact__input">
                        <input type="mail" placeholder="Email" class="contact__input">
                        <textarea name="" id="" cols="0" rows="10" class="contact__input"></textarea>
                        <input type="button" value="Enter" class="contact__button button">
                    </form>
                </div>
            </section>
        </main>

        <!--===== FOOTER =====-->
        <footer class="footer">
            <p class="footer__title">Kirupanandhan</p>
            <div class="footer__social">
                <a href="#" class="footer__icon"><i class='bx bxl-facebook' ></i></a>
                <a href="#" class="footer__icon"><i class='bx bxl-instagram' ></i></a>
                <a href="#" class="footer__icon"><i class='bx bxl-twitter' ></i></a>
            </div>
          
        </footer>
    </body>
</html>
```

### Style.css
```

@import url("https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;700&display=swap");
/*===== VARIABLES CSS =====*/
:root{
  --header-height: 3rem;
  --font-semi: 600;
}

/*===== Colores =====*/
:root{
  --first-color: #d61e87;
  --second-color: #0E2431;
}


:root{
  --body-font: 'Poppins', sans-serif;
  --big-font-size: 2rem;
  --h2-font-size: 1.25rem;
  --normal-font-size: 0.938rem;
}


/*===== Margenes =====*/
:root{
  --mb-1: 0.5rem;
  --mb-2: 1rem;
  --mb-3: 1.5rem;
  --mb-4: 2rem;
  --mb-5: 2.5rem;
  --mb-6: 3rem;
}

/*===== z index =====*/
:root{
  --z-back: -10;
  --z-normal: 1;
  --z-tooltip: 10;
  --z-fixed: 100;
}

/*===== BASE =====*/
*,::before,::after{
  box-sizing: border-box;
}
html{
  scroll-behavior: smooth;
}
body{
  margin: var(--header-height) 0 0 0;
  font-family: var(--body-font);
  font-size: var(--normal-font-size);
  color: var(--second-color);
}
h1,h2,p{
  margin: 0;
}
ul{
  margin: 0;
  padding: 0;
  list-style: none;
}
a{
  text-decoration: none;
}
img{
  max-width: 100%;
  height: auto;
  display: block;
}

/*===== CLASS CSS ===== */
.section-title{
  position: relative;
  font-size: var(--h2-font-size);
  color: var(--first-color);
  margin-top: var(--mb-2);
  margin-bottom: var(--mb-4);
  text-align: center;
}
.section-title::after{
  position: absolute;
  content: "";
  width: 64px;
  height: 0.18rem;
  left: 0;
  right: 0;
  margin: auto;
  top: 2rem;
  background-color: var(--first-color);
}
.section{
  padding-top: 3rem;
  padding-bottom: 2rem;
}

/*===== LAYOUT =====*/
.bd-grid{
  max-width: 1024px;
  display: grid;
  grid-template-columns: 100%;
  grid-column-gap: 2rem;
  width: calc(100% - 2rem);
  margin-left: var(--mb-2);
  margin-right: var(--mb-2);
}
.l-header{
  width: 100%;
  position: fixed;
  top: 0;
  left: 0;
  z-index: var(--z-fixed);
  background-color: #fff;
  box-shadow: 0 1px 4px rgba(146,161,176,.15);
}

/*===== NAV =====*/
.nav{
  height: var(--header-height);
  display: flex;
  justify-content: space-between;
  align-items: center;
  font-weight: var(--font-semi);
}


.nav__item{
  margin-bottom: var(--mb-4);
}
.nav__link{
  position: relative;
  color: #fff;
}
.nav__link:hover{
  position: relative;
}
.nav__link:hover::after{
  position: absolute;
  content: "";
  width: 100%;
  height: 0.18rem;
  left: 0;
  top: 2rem;
  background-color: var(--first-color);
}
.nav__logo{
  color: var(--second-color);
}
.nav__toggle{
  color: var(--second-color);
  font-size: 1.5rem;
  cursor: pointer;
}

/*Active menu*/
.active::after{
  position: absolute;
  content: "";
  width: 100%;
  height: 0.18rem;
  left: 0;
  top: 2rem;
  background-color: var(--first-color);
}

/*=== Show menu ===*/
.show{
  right: 0;
}

/*===== HOME =====*/
.home{
  height: calc(100vh - 3rem);
  row-gap: 1rem;
}
.home__data{
  align-self: center;
}
.home__title{
  font-size: var(--big-font-size);
  margin-bottom: var(--mb-5);
}
.home__title-color{
  color: var(--first-color);
}
.home__social{
  
  display: flex;
  flex-direction: column;
  
}
.home__social-icon{
  width: max-content;
  margin-bottom: var(--mb-2);
  font-size: 1.5rem;
  color: var(--second-color);
}
.home__social-icon:hover{
  color:#c51780
}
.home__img{
  position: absolute;
  right: 0;
  bottom: 0;
  width: 295px;
}

/*BUTTONS*/
.button{
  display: inline-block;
  background-color: var(--first-color);
  color: #fff;
  padding: .75rem 2.5rem;
  font-weight: var(--font-semi);
  border-radius: .5rem;
}
.button:hover{
  box-shadow: 0 10px 36px rgba(0,0,0,.15);
}

/* ===== ABOUT =====*/
.about__container{
  row-gap: 2rem;
  text-align: center;
}
.about__subtitle{
  margin-bottom: var(--mb-2);
}
.about__img{
  justify-self: center;
}
.about__img img{
  width: 200px;
  border-radius: .5rem;
}

/* ===== SKILLS =====*/
.skills__container{
  row-gap: 2rem;
  text-align: center;
}
.skills__subtitle{
  margin-bottom: var(--mb-2);
}
.skills__text{
  margin-bottom: var(--mb-4);
}
.skills__data{
  display: flex;
  justify-content: space-between;
  align-items: center;
  position: relative;
  font-weight: var(--font-semi);
  padding: .5rem 1rem;
  margin-bottom: var(--mb-4);
  border-radius: .5rem;
  box-shadow: 0 4px 25px rgba(14,36,49,.15);
}
.skills__icon{
  font-size: 2rem;
  margin-right: var(--mb-2);
  color: var(--first-color);
}
.skills__names{
  display: flex;
  align-items: center;
}
.skills__bar{
  position: absolute;
  left: 0;
  bottom: 0;
  background-color: var(--first-color);
  height: .25rem;
  border-radius: .5rem;
  z-index: var(--z-back);
}
.skills__html{
  width: 95%;
}
.skills__css{
  width: 85%;
}
.skills__js{
  width: 65%;
}
.skills__ux{
  width: 75%;
}
.skills__img{
  border-radius: .5rem;
}

/* ===== WORK =====*/
.work__container{
  row-gap: 2rem;
}
.work__img{
  box-shadow: 0 4px 25px rgba(14,36,49,.15);
  border-radius: .5rem;
  overflow: hidden;
}
.work__img img{
  transition: 1s;
  cursor: pointer;
}
.work__img img:hover{
  transform: scale(1.1);
}

/* ===== CONTACT =====*/
.contact__input{
  width: 100%;
  font-size: var(--normal-font-size);
  font-weight: var(--font-semi);
  padding: 1rem;
  border-radius: .5rem;
  border: 1.5px solid var(--second-color);
  outline: none;
  margin-bottom: var(--mb-4);
}
.contact__button{
  display: block;
  border: none;
  outline: none;
  font-size: var(--normal-font-size);
  cursor: pointer;
  margin-left: auto;
}

/* ===== FOOTER =====*/
.footer{
  background-color:#4f0933 ;
  color: #fff;
  text-align: center;
  font-weight: var(--font-semi);
  padding: 2rem 0;
}
.footer__title{
  font-size: 2rem;
  margin-bottom: var(--mb-4);
}
.footer__social{
  margin-bottom: var(--mb-4);
}
.footer__icon{
  font-size: 1.5rem;
  color: #fff;
  margin: 0 var(--mb-2)
}
.footer__icon:hover{
 
  color: #d61e87;
  
}

/* ===== MEDIA QUERIES=====*/
@media screen and (min-width: 768px){
  body{
    margin: 0;
  }
  .section{
    padding-top: 4rem;
    padding-bottom: 3rem;
  }
  .section-title{
    margin-bottom: var(--mb-6);
  }
  .section-title::after{
    width: 80px;
    top: 3rem;
  }

  .nav{
    height: calc(var(--header-height) + 1rem);
  }
  .nav__list{
    display: flex;
    padding-top: 0;
  }
  .nav__item{
    margin-left: var(--mb-6);
    margin-bottom: 0;
  }
  .nav__toggle{
    display: none;
  }
  .nav__link{
    color: var(--second-color);
  }

  .home{
    height: 100vh;
  }
  .home__data{
    align-self: flex-end;
  }
  .home__social{
    padding-top: 0;
    padding-bottom: 2.5rem;
    flex-direction: row;
    align-self: flex-end;
  }
  .home__social-icon{
    margin-bottom: 0;
    margin-right: var(--mb-4);
  }
  .home__img{
    width: 457px;
    bottom: 15%;
  }

  .about__container, .skills__container{
    grid-template-columns: repeat(2,1fr);
    align-items: center;
    text-align: initial;
  }
  .about__img img{
    width: 300px;
  }
  .work__container{
    grid-template-columns: repeat(3, 1fr);
    grid-template-rows: repeat(2,1fr);
    column-gap: 2rem;
  }
  .contact__form{
    width: 360px;
  }
  .contact__container{
    justify-items: center;
  }
}

@media screen and (min-width: 1024px) {
  .bd-grid {
    margin-left: auto;
    margin-right: auto;
  }
  .home__img {
    right: 10%;
  }
}

```
## Output:-
![image](https://github.com/Kirupanandhan/To-create-a-web-Portfolio-CV-using-HTML-CSS/assets/94386222/cc776604-1328-4c2b-8277-4c5850a29b94)

![image](https://github.com/Kirupanandhan/To-create-a-web-Portfolio-CV-using-HTML-CSS/assets/94386222/1e9336b3-4c12-4719-a381-cfcf572f7b1b)

![image](https://github.com/Kirupanandhan/To-create-a-web-Portfolio-CV-using-HTML-CSS/assets/94386222/e14d74ce-6485-421f-9c55-20c1f52c779b)

![image](https://github.com/Kirupanandhan/To-create-a-web-Portfolio-CV-using-HTML-CSS/assets/94386222/c9a005ae-5a34-452b-bc62-37002fb06dca)

![image](https://github.com/Kirupanandhan/To-create-a-web-Portfolio-CV-using-HTML-CSS/assets/94386222/1e2a18aa-6876-4165-b0cd-3ea70d301120)


## Result:-
Thus the program To created a web Portfolio/CV using HTML & CSS Successfully
