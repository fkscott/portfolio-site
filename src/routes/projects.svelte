<svelte:head>
    <title>F. Keagan Scott - Projects</title>
</svelte:head>

<script>
    import Card from '../lib/Card.svelte';
</script>
<main>
<div class="container" id="project-container">

    <div class="row pt-5">
        <div class="col-md-12">
            <h1 class="project-heading">projects</h1>
        </div>
    </div>


    <div class="row d-flex justify-content-center">
        <div class="col-md-4">
            <Card
                cardTitle={"Shelf Talker Tool"}
                cardDescription={"A single page Svelte app to generate shelf talkers for use at The Wine Merchant. All processing is done client-side, and uses HTML2Canvas to create data URLs to export the generated shelf talkers."}
                cardLink={"https://wm-shelf-talker.vercel.app/"}
            ></Card>
        
        </div>
        <div class="col-md-4">
            <Card
                cardTitle={"Incipiam"}
                cardDescription={"Using bash and launchd, this script launches and closes certain processes when I connect my Mac to my USB-C monitor"}
                cardLink={"https://github.com/fkscott/incipiam"}
            ></Card>
        </div>
    </div>

    <div class="row d-flex justify-content-center">
        <div class="col-md-4">
            <Card
                cardTitle={"Acorn Supply"}
                cardDescription={"Website design for a local Baltimore construction company. I was tasked with creating a single page site that highlighted their certifications, NAICS codes, and contact information."}
                cardLink={"https://fkscott.github.io/acorn/"}
            ></Card>
        
        </div>
        <div class="col-md-4">
            <Card
                cardTitle={"PcPartPicker to CSV"}
                cardDescription={"Simple Python web scraper to take a PcPartPicker list and export it into CSV format"}
                cardLink={"https://github.com/fkscott/pcpartpicker-scraper"}
            ></Card>
        </div>
    </div>

    <div class="row d-flex justify-content-center">
        <div class="col-md-4">
            <Card
                cardTitle={"All About GT3"}
                cardDescription={"Static site designed for my Web I coursework. It uses HTML, CSS, and vanilla Javascript to show different information about the GT3 class of touring car racing"}
                cardLink={"https://www.web1projects.com/2021/keagan-scott/index.html"}
            ></Card>
        </div>
    </div>
</div>
</main>

<style>
    #project-container{
        max-width: 1200px;
    }
    .project-heading{
        font-family: 'Romana', serif;
        font-size: 48pt;
    }

    @media screen and (max-width: 768px){
        .project-heading{
            font-size: 32pt;
        }
    }
</style>