
<html>
    <head>
        <title>My Portfolio</title>
        <link rel="stylesheet" href="truefolio.css">

        <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.7.2/css/all.min.css" integrity="sha512-Evv84Mr4kqVGRNSgIGL/F/aIDqQb7xQ2vcrdIwxfjThSH8CSR7PBEakCr51Ck+w+/U6swU2Im1vVX0SVk9ABhg==" crossorigin="anonymous" referrerpolicy="no-referrer" />
    </head>
    <body>
        <header>
            <a href="#" class="logo">TALHA CHAUDHARY</a>

            <nav>
                <a href="#" class="active">HOME</a>
                <a href="#">SERVICES</a>
                 <a href="#">EDUCATION</a>
                 <a href="#">EXPERIENCE</a>
                 <a href="https://api.whatsapp.com/send/?phone=%2B923404040529&text&type=phone_number&app_absent=0">CONTACT</a>
            </nav>
        </header>
        <section class="home">
            <div class="home-img">
                <img src="c:\Users\Hajvery\Desktop\IP11\IMG_0529 (1).JPG" alt="">
            </div>
            <div class="home-content">
                <h1>Hi It's <span>TALHA</span></h1>
                <script>
                    alert("HEY EVERYONE! WELCOME TO MY WEBSITE")
                </script>
                <h3 class="typing text">I'm a  <span>web Developer</span></h3>
                <p style="font-size: medium;">HEY!I am boy who is student of grade 9 in PAKISTAN.My school name is AMERICAN LYCEUM INTERNATIONAL SCHOOL.I'm a full-stack developer.I have leanrt this web developing from my SIR ABDUL RAHIM AMIR.</p>
                <h2 class="her2">His portfolio:</h2>
                <a href="https://abdulrahimamir.vercel.app/" class="sirfolio">Rahim's Portfolio</a>
                <div class="social-icons">
                    <a href="#"><i class="fa-brands fa-linkedin"></i></a>
                    <a href="https://github.com/CHAUDHARY5182"><i class="fa-brands fa-github"></i></a>
                    <a href="#"><i class="fa-brands fa-x-twitter"></i></a>
                    <a href="https://www.tiktok.com/@chaudhary5182"><i class="fa-brands fa-tiktok"></i></a></i></a>
                    <a href="https://www.instagram.com/@arain_zada_2"><i class="fa-brands fa-instagram"></i></a>
                </div>
                <a href="mailto:chaudharytalha5182@gmail.com" class="btn">Hire Me</a></a>
            </div>
        </section>
    </body>
</html>

*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    text-decoration: none;
    border: none;
    outline: none;
    font-family: 'poppins',sans-serif;
}

html{
    font-size: 62.5%;
}

body{
    width: 100%;
    height: 100vh;
    overflow-x: hidden;
    background-color: black;
    color: white;
}

header{
    margin-top: 20px;
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    padding: 1rem 9%;
    background-color: transparent;
    filter: drop-shadow(10px);
    display: flex;
    justify-content: space-between;
    align-items: center;
    z-index: 100;
}

.logo{
    font-size: 3rem;
    color: #b74b4b;
    font-weight: 800;
    cursor: pointer;
    transition:0.5s ease;
}

.logo:hover{
    transform: scale(1.1);
}

nav a{
    font-size: 1.8rem;
    color: white;
    margin-left: 4rem;
    font-weight: 500;
    transition: 0.3s ease;
    border-bottom: 3px solid transparent;
}

nav a:hover,
nav a.active{
    color: #b74b4b;
    border: 3px solid #b74b4b;
}

@media(max-width:995px){
    nav{
        position: absolute;
        display: none;
        top: 0;
        right: 0;
        width: 40%;
        border-left:3px solid #b74b4b;
        border-bottom: 3px solid #b74b4b;
        border-bottom-left-radius: 2rem;
        padding: 1rem;
        background-color: #161616;
        border-top: #161616;
    }

    nav.active{
        display: block;
    }

    nav a{
        display: block;
        font-size: 2rem;
        margin: 3rem 0;
    }

    nav a:hover,
    nav a.active{
        padding: 1rem;
        border-radius: 0.5rem;
        border-bottom: 0.5rem solid #b74b4b;
    }
}

section{
    min-height: 100vh;
    padding:5rem 9% 5rem;
}

.home{
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 8rem;
    background-color: rgb(0, 0, 0);
}

.home.home-content h1{
    font-size: 6rem;
    font-weight: 700;
    line-height: 1.3;
}

span{
    color: #b74b4b;
}

.home-content h3{
    font-size: 4rem;
    margin-bottom: 1rem;
    font-weight: 700;
}

.home-img{
    border-radius: 50%;
}

.home-img img{
    position: relative;
    width:32vw;
    border-radius: 50%;
    box-shadow: 0 0 25px #b74b4b;
    cursor: pointer;
    transition: 0.2s linear;
}

.home-img img:hover{
    font-size: 1.8rem;
    font-weight: 500;
}

.social-icons a{
    display: inline-flex;
    justify-content: center;
    align-items: center;
    width: 4rem;
    height: 4rem;
    background-color: transparent;
    border:0.2rem solid #b74b4b;
    font-size: 2rem;
    border-radius: 50%;
    margin: 3rem 1.5rem 3rem 0;
    transition: 0.3s ease;
    color: #b74b4b;
}

.social-icons a:hover{
    color: black;
    transform: scale3d(1.3) translateY(-5px);
    background-color: #b74b4b;
    box-shadow: 0 0 25px #b74b4b;
}

.btn{
    display: inline-block;
    padding: 1rem 2.8rem;
    background-color: black;
    border-radius: 4rem;
    font-size: 1.6rem;
    color: #b74b4b;
    letter-spacing: 0.3rem;
    font-weight: 600;
    border: 2px solid #b74b4b;
    transition: 0.3s ease;
    cursor: pointer;
}

.btn:hover{
    transform: scale3d(1.03);
    background-color: #b74b4b;
    color: black;
    box-shadow: 0 0 25px #b74b4b;
}

.typing-text{
    font-size: 34px;
    font-weight: 600;
    min-width: 280px;
}

.typing-text span{
    position: relative;
}

.typing-text span::before{
    content:Software Developer;
    color: #b74b4b;
    animation: words 20s infinite;
}
.typing-text::after{
    content: "";
    background-color: black;
    position: absolute;
    width: calc(100% + 8px);
    height: 100%;
    border-left: 3px solid black;
    right: -8px;animation:cursor 0.6 infinite;
}


@keyframes cursor{
    to{
        border-left: 3px solid #b74b4b;
    }
}

@keyframes words{
    0%,20%{
        content:"Web Developer";
    }
    21%,40%{
        content: "Software Developer";
    }
    41%,60%{
        content: "Web Devsigner";
    }
    61%,80%{
        content: "TikToker";
    }
    81%,100%{
        content: "Script Writer";
    }
}

.her2{
    color: white;
    font-size: xx-large;
}
.sirfolio{
    color: #b74b4b;
    font-size: medium;
}

@media(max-width:1000px){
    .home{
        gap:4rem;
    }
}

@media(max-width:995px){
    .home{
        flex-direction: column;
        margin: 5rem 4rem;
    }

    .home.home-content h3{
        font-size: 2.5rem;
    }

    .home-content h1{
        font-size: 5rem;
    }

    .home-img img{
        width: 70vh;
        margin-top: 4rem;
    }
}

