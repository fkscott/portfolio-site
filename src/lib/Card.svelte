<script>
    export let cardTitle;
    export let cardDescription;
    export let cardLink;
 </script>
 
 <main>
     <div class="container py-3">
         <div class="project-card p-2 d-flex flex-column">
             <h3 class="card-title">{cardTitle}</h3>
             <p class="card-body">{cardDescription}</p>
 
             <div class="link-container py-3 d-flex justify-content-center align-items-end">
 
                 <a class="card-link text-center d-flex align-items-center justify-content-center" href={cardLink} target="_blank">view</a>
             </div>
         </div>
     </div>
 </main>
 
 <style>
 
     .project-card{
         background-color: white;
         transition: 0.2s;
         height: 400px;

         max-width: 368px;
     }
 
     .card-title{
         font-family: 'Raleway', sans-serif;
         font-weight: 600;
        margin: 10px;
     }
 
     .card-body{
        
         font-family: 'Raleway', sans-serif;
         font-weight: 400;
         font-size: 12pt;
     }
 
     .card-link{
         width: 200px;
         height: 50px;
         background-color: #40798C;
         color: white;
 
         text-decoration: none;
         font-size: 16pt;
         font-family: 'Raleway', sans-serif;
         font-weight: 600;
 
         transition: 0.2s; 
 
     }
 
     .card-link:hover{
         background-color: #4D91A8;
     }
 
 </style>