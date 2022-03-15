
<svelte:head>
    <title>F. Keagan Scott</title>
</svelte:head>


<main>
    <div class="container" id="home-container">

        <!-- start actual home content -->
        <div class="row pt-5">
            <div class="col-md-12 d-flex justify-content-center" id="name">
                <h1>F. Keagan Scott</h1>
            </div>
        </div>

        <div class="row">
            <div class="col-md-12 d-flex justify-content-center" id="tagline">
                <h3>Developer & Designer</h3>
            </div>
        </div>

        <div class="row p-3">
            <div class="col-md-12 d-flex justify-content-center" id="about-text">
                <p class="lead">
                    Hello! My name is Keagan. I am currently a QA Engineer and aspiring Web Developer. This site contains information about myself and the projects I’ve worked on.
                </p>
            </div>
        </div>

        <div class="row py-3 justify-content-center">
            <a href="/about" class="col-md-6 px-3 project-link text-center d-flex align-items-center justify-content-center">
                about me
            </a>
            <a href="/projects" class="col-md-6 px-3 project-link text-center d-flex align-items-center justify-content-center">
                projects
            </a>
        </div>

        <div class="row py-3 socials justify-conent-center">
            <div class="col-md-12 d-flex align-items-center justify-content-center">
                <a href="https://www.linkedin.com/in/f-keagan-scott-5a8ab6187/" target="_blank"><img src ="./img/icons/linkedin.svg" alt="linkedin icon"></a>
                <a href="https://github.com/fkscott" target="_blank"><img src ="./img/icons/github.svg" alt="github icon"></a>
            </div>
        </div>
    </div>



</main>

<style>

    #home-container{
        max-width: 1200px;
    }

    h1{
        font-size: 72pt;
		font-family: 'Romana', serif;
        text-align: center;
        transition: 0.2s
	}

	h3{
        font-size: 48pt;
		font-family: 'Romana', serif;
        text-align: center;
        transition: 0.2s
	}

    #about-text{
        font-family: HiraginoRegular, 'sans-serif';
    }

    .project-link{
        font-family: 'HiraginoBold', sans-serif;
        color: white;
        background-color: #40798C;
        text-decoration: none;
        font-size: 18pt;
        
        max-width: 225px;
        height: 70px;

        margin: 20px;
        transition: 0.2s;


    }

    .project-link:hover{
        background-color: #4D91A8;
    }


    .socials img{
        width: 80px;
        height: auto;
        filter: invert(8%) sepia(13%) saturate(4%) hue-rotate(332deg) brightness(95%) contrast(92%);
        transition: 0.2s;
    }

    .socials img:hover{
        filter: invert(54%) sepia(9%) saturate(2220%) hue-rotate(149deg) brightness(95%) contrast(86%);    
    }
    .socials a {
        text-decoration: none;
        padding-inline: 20px;
    }

    @media screen and (max-width: 768px){
        h1{
            font-size: 36pt;
        }

        h3{
            font-size: 24pt;
        }

        .project-link{
            width: 225px;
        }
    }
</style>