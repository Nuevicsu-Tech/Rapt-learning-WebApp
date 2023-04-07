<script>
    import rapt from '$lib/images/rapt.png';
    import hero from '$lib/images/hero.png';
</script>

<main>
    <section class="Navigation-Section">
        <nav class="Large-Nav navbar navbar-expand-lg navbar-light ">
            <a class="navbar-brand" href="#">
              <img src={rapt} width="60" height="60" class="d-inline-block align-top" alt="Brand Icon">
            </a>
    
            <div class="collapse navbar-collapse" id="navbarNav">
              <ul class="navbar-nav mx-auto">
                <li class="nav-item ">
                  <a class="nav-link Active-Link" href="/">Home</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link" href="/courses">Courses</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link" href="/about">About</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="/contact">Contact</a>
                  </li>
              </ul>
            </div>
        </nav>
    </section>
    <section class="Hero-Section">
        <div class="container-fluid">
            <div class="Main-Row row">
                <div class="Hero-Text col-lg-6">
                    <h1><span>E</span>-Learning <br>Made Rapt &<br> Fascinating</h1> 
                    <br>
                    <p>Best place to learn <span >programming</span> with beginner friendly tutorials</p>
                    <br>
                    <a href="" class="btn btn-primary Hero-Button">Start Coding Now</a>
                </div>

                <div class="col-lg-6" style="text-align: center;">
                    <img src={hero} width="90%" alt="">
                </div>

            </div>
        </div>
    </section>
    
</main>

<style>
/* Large NavBar */
    .Large-Nav{
        padding-left: 6rem;
        padding-right: 6rem;
    }
    .Large-Nav .nav-link{
        color: white;
        font-weight: 400;
        font-size: larger;
        padding-right: 2rem;
        padding-left: 2rem;



    }
    .Large-Nav a:hover{
        color: #9b26b6;
        font-weight: 600;

    }
    .Large-Nav a.Active-Link{
        color: #9b26b6;
        font-weight: 600;
        border-bottom: solid 3px #9b26b6;


    }
    /* Large Hero */
    .col-lg-6{
        padding: 3rem 6rem 5rem;
    }
    .Hero-Text h1{
        font-size: 5rem;
        color: white;
    }
    .Hero-Text span{
        color: #9b26b6;
    }
    .Hero-Text p{
        font-size: 1.5rem;
        color: white;
    }
    .Hero-Button{
        background-color: #9b26b6;
        border-color: #9b26b6;
    }
    .Hero-Button:hover{
        background-color: #790294;
        border-color: #790294;
    }
    
</style>
  