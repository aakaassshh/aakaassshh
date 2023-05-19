<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8" />
        <meta http-equiv="X-UA-Compatible" content="IE=edge" />
        <meta name="viewport" content="width=device-width, initial-scale=1.0" />
          <style>
          
          html{
    scroll-behavior: smooth;
}

.cover{
    background:no-repeat, linear-gradient(rgba(0, 0, 0, .5), rgba(0, 0, 0, .5)), url("https://images.unsplash.com/photo-1506784693919-ef06d93c28d2?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=870&q=80") no-repeat;
    background-size: cover;
    min-height: 100vh;
}
.cover-content{
    min-height: 100vh;
}
.cover-content img{

    max-width: 200px;
    border:2px solid white;
}

.about{
    background-color: #ececec;
}

@media screen and (max-width: 760px) {
    .cover-content h1{
        font-size: 36px;
        font-weight: bold;
        padding-top: 30px;
    }

    .cover-content h6{
        font-size: 15px;
    }
}
/* 
img:hover
{
	border-radius: 50%;
	box-shadow: 10px 10px 10px black;
	scale: 3;
	transition-duration: 2s;

}    */

img:hover {
    transform: scale(1.2); /* Increase the size of the image on hover */
    /* filter: grayscale(100%);  */
    /* filter: blur(5px); */

    /* filter: brightness(150%); */

    /* opacity: 0.7; */
    /* transform: rotate(20deg); */

  }
  
        </style>




        <title>Document</title>
        <link
            href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css"
            rel="stylesheet"
            integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC"
            crossorigin="anonymous"
        />
        <!-- <link rel="stylesheet" href="style.css"> -->
    </head>
    <body data-bs-spy="scroll" data-bs-target="#nav-scroll" data-offset="56">
        <header class="Header" id="home">
            <nav id="nav-scroll" class="navbar navbar-expand-lg navbar-dark bg-dark fixed-top">
                <div class="container">
                    <a href="#" class="navbar-brand">Portfolio</a>
                    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbar" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                        <span class="navbar-toggler-icon"></span>
                    </button>
                    <div class="collapse navbar-collapse" id="navbar">
                        <ul class="navbar-nav mx-auto">
                            <li class="nav-item">
                                <a href="#home" class="nav-link">Home</a>
                            </li>
                            <li class="nav-item">
                                <a href="#portfolio" class="nav-link">Portfolio</a>
                            </li>
                            <li class="nav-item">
                                <a href="#about" class="nav-link">About</a>
                            </li>
                            <li class="nav-item">
                                <a href="#contact" class="nav-link">Contact</a>
                            </li>
                        </ul>
                    </div>
                </div>
            </nav>
            <div class="cover container-fluid text-white">
                <div class="cover-content d-flex flex-column justify-content-center align-items-center">
                    <img   width="100%" height="300px"class="rounded-circle" alt="" src="IMG_5986 Copy-02 (1).jpeg">
                    <h1 class="display-2 text-capitalize"> AKASH KHANDAL</h1>
                    <h6 class="pt-3 h4"> - Software Developer - </h6>
                </div>
            </div>

        </header>

        <section class="container py-5" id="portfolio">
            <div class="section-title text-center pt-2">
                <h1 class="h1 pb-2">Portfolio</h1>
                <p class="text-muted"> Projects Uploading soon</p>
            </div>
            <div class="row">
                <div class="col-lg-4 col-md-6 mb-5">
                    <img class="img-fluid img-thumbnail" src="https://images.unsplash.com/photo-1542831371-29b0f74f9713?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxzZWFyY2h8Mnx8cHJvZ3JhbW1pbmd8ZW58MHwwfDB8fA%3D%3D&auto=format&fit=crop&w=600&q=60">
                </div>
                <div class="col-lg-4 col-md-6 mb-5">
                    <img class="img-fluid img-thumbnail" src="https://images.unsplash.com/photo-1605379399642-870262d3d051?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxzZWFyY2h8MXx8cHJvZ3JhbW1pbmd8ZW58MHwwfDB8fA%3D%3D&auto=format&fit=crop&w=600&q=60">
                </div>
                <div class="col-lg-4 col-md-6 mb-5">
                    <img class="img-fluid img-thumbnail" src="https://images.unsplash.com/photo-1571171637578-41bc2dd41cd2?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxzZWFyY2h8NHx8cHJvZ3JhbW1pbmd8ZW58MHwwfDB8fA%3D%3D&auto=format&fit=crop&w=600&q=60">
                </div>
                <div class="col-lg-4 col-md-6 mb-5">
                    <img class="img-fluid img-thumbnail" src="https://images.unsplash.com/photo-1542831371-29b0f74f9713?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxzZWFyY2h8Mnx8cHJvZ3JhbW1pbmd8ZW58MHwwfDB8fA%3D%3D&auto=format&fit=crop&w=600&q=60">
                </div>
                <div class="col-lg-4 col-md-6 mb-5">
                    <img class="img-fluid img-thumbnail" src="https://images.unsplash.com/photo-1605379399642-870262d3d051?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxzZWFyY2h8MXx8cHJvZ3JhbW1pbmd8ZW58MHwwfDB8fA%3D%3D&auto=format&fit=crop&w=600&q=60">
                </div>
                <div class="col-lg-4 col-md-6 mb-5">
                    <img class="img-fluid img-thumbnail" src="https://images.unsplash.com/photo-1571171637578-41bc2dd41cd2?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxzZWFyY2h8NHx8cHJvZ3JhbW1pbmd8ZW58MHwwfDB8fA%3D%3D&auto=format&fit=crop&w=600&q=60">
                </div>
            </div>
        </section>
        <section class="about" id="about">
            <div class="container about-content">
                <div class="section-title text-center pt-2">
                    <h1 class="h1 pb-2">About Me</h1>
                    <p class="text-muted">Student <br>
                           Learning  New Langauges<br>
                              Frontend || Backend
                    </p>
                    

                </div>
                <div class="row">
                    <div class="col-md-6">
                        <h3 class="text-center pt-5 pb-3">Who Am I?</h3>
                        <p style="text-align: justify" class="text-muted">" I am a software developer, someone who uses their expertise and creativity to build digital solutions and bring ideas to life. I am passionate about crafting code and developing software applications that solve real-world problems and enhance user experiences. My role involves analyzing requirements, designing and implementing software systems, debugging and testing programs, and collaborating with teams to ensure successful project delivery.

                            I thrive in the realm of technology, constantly adapting to the ever-evolving landscape of programming languages, frameworks, and tools. I possess strong problem-solving skills and attention to detail, meticulously transforming complex concepts into efficient and elegant code structures. As a software developer, I value clean and maintainable code, embracing best practices and coding standards to facilitate teamwork and future scalability.
                            
                            Beyond writing code, I am a lifelong learner. I actively engage in continuous professional development, staying up-to-date with industry trends, attending conferences, and participating in online communities. I enjoy tackling new challenges and honing my skills in areas such as web development, mobile applications, databases, and software architecture.
                            
                            Ultimately, as a software developer, I am driven by the opportunity to make a meaningful impact through technology. I have the power to create innovative solutions, streamline processes, and improve lives through the software applications I develop. I am proud to be a software developer, constantly pushing the boundaries of what is possible in the digital world."
                            
                            
                            
                            
                            </p>
                        <p style="text-align: justify" class="text-muted"></p>
                    </div>
                    <div class="col-md-6">
                        <h3 class="text-center pt-5 pb-3">What Skills Do I Have?</h3>
                        <h6>Html:</h6>
                        <div class="progress my-2 border border-primary bg-white">
                            <div class="progress-bar progress-bar-striped progress-bar-animated" role="progressbar" aria-valuemin="0" aria-valuemax="100" aria-valuenow="75" style="width: 74%">75%</div>
                        </div>
                        <h6>Css:</h6>
                        <div class="progress my-2 border border-success bg-white">
                            <div class="progress-bar progress-bar-striped progress-bar-animated bg-success" role="progressbar" aria-valuemin="0" aria-valuemax="100" aria-valuenow="50" style="width: 50%">50%</div>
                        </div>
                        <h6>Javascript:</h6>
                        <div class="progress my-2 border border-warning bg-white">
                            <div class="progress-bar progress-bar-striped progress-bar-animated bg-warning" role="progressbar" aria-valuemin="0" aria-valuemax="100" aria-valuenow="40" style="width: 40%">40%</div>
                        </div>
                        <h6>Bootstrap:</h6>
                        <div class="progress my-2 border border-danger bg-white">
                            <div class="progress-bar progress-bar-striped progress-bar-animated bg-danger" role="progressbar" aria-valuemin="0" aria-valuemax="100" aria-valuenow="20" style="width: 20%">20%</div>
                        </div>
                        <h6>Java</h6>
                        <div class="progress my-2 border border-info bg-white">
                            <div class="progress-bar progress-bar-striped progress-bar-animated bg-info" role="progressbar" aria-valuemin="0" aria-valuemax="100" aria-valuenow="70" style="width: 70%">70%</div>
                        </div>
                    </div>
                </div>

            </div>
        </section>

        <section class="contact" id="contact">
            <div class="container py-5">
                <div class="section-title text-center pt-2">
                    <h1 class="h1 pb-2">Contact Me</h1>
                    <p class="text-muted">You can contact me throught this following sites</p>
                </div>
                <div class="row">
                    <form action="#" class="col-md-10 mx-auto py-5">
                        <div class="form-group mb-3">
                            <label for="name">Name</label>
                            <input id="name" type="text" class="form-control">
                        </div>
                        <div class="form-group mb-3">
                            <label for="email">Email Address</label>
                            <input id="email" type="email" class="form-control">
                            <small class="form-text text-muted">We'll never share your email with anyone else.</small>
                        </div>
                        <div class="form-group mb-3">
                            <label for="message">Message</label>
                            <input id="message" type="text" class="form-control">
                        </div>
                        <div class="form-group mb-3">
                            <input id="checkbox" type="checkbox" class="form-check-input">
                            <label class="form-check-label" for="checkbox">Check me out</label>
                        </div>
                        <button class="btn btn-primary" type="submit">Submit</button>
                    </form>
                </div>
            </div>
        </section>


        <footer class="text-center bg-dark mb-0 py-4">
            <div class="container">
                <p class="text-white m-0">@All Right Reserved || made by (Akash Khandal)</p>
                <div class="mt-2">
                    <!-- Replace the "#" with your social media profile URLs -->
                    <a href="#" target="_blank"><img src="images.png" alt="Instagram" width="30" height="30"></a>
                    <a href="#" target="_blank"><img src="twitter.png" alt="Twitter" width="30" height="30"></a>
                    <a href="#" target="_blank"><img src="download (1).jfif" alt="LinkedIn" width="30" height="30"></a>
                    <!-- Add more social media links and logos as needed -->
                </div>
            </div>
        </footer>

          

        <!-- Scripts -->
        <script
            src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.2/dist/umd/popper.min.js"
            integrity="sha384-IQsoLXl5PILFhosVNubq5LC7Qb9DXgDA9i+tQ8Zj3iwWAwPtgFTxbJ8NT4GN1R8p"
            crossorigin="anonymous"
        ></script>
        <script
            src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.min.js"
            integrity="sha384-cVKIPhGWiC2Al4u+LWgxfKTRIcfu0JTxR+EQDz/bgldoEyl4H0zUF0QKbrJ0EcQF"
            crossorigin="anonymous"
        ></script>
    </body>
</html>
