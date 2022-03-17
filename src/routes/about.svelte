<svelte:head>
    <title>F. Keagan Scott - About</title>
</svelte:head>

<script>
    import Skills from '../lib/Skills.svelte'
</script>
<main>
    <div class="container px-3" id="about-container">
        <div class="row pt-5">
            <div class="col-md-6 p-3">
                <h1 class="project-heading">about</h1>

                <p class="lead" id="about-me">
                    My name is Frederic, but I go by my middle name: Keagan. I am a senior Computer Science major at Loyola University Maryland and am excited to be entering the software engineering field. I have a passion for the way computer programs look and feel. This is due in part to my education. In addition to the computer science curriculum, I have been able to take classes dedicated to art and graphic design which helped me realize how important the visuals are in modern web applications. Ultimately, I want to work as a software engineer with a focus UI / UX. I currently work at ECS Tuning as a QA Engineer where I have been developing manual and automated testing suites for new software features.  
                </p>
            </div>

            <div class="col-md-6 p-3">
                <h1 class="project-heading">skills</h1>
                <Skills></Skills>
            </div>
        
        </div>
    </div>
</main>


<style>

    #about-container{
        max-width: 1200px;
    }

    #about-me{
        font-family: 'Raleway', sans-serif;
        font-weight: 400;
    }
    .project-heading{
        font-family: 'Romana', serif;
        font-size: 48pt;
        transition: 0.2s;
    }

    @media screen and (max-width: 768px){
        .project-heading{
            font-size: 32pt;
        }
    }
</style>