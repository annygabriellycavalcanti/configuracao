<script setup lang="ts">
 
</script>
 
<template>
 <section class="py-5 mt-5">
        <div class="container py-4 py-xl-5">
            

          <div class="accordion accordion-flush" id="accordionFlushExample">
        <div class="accordion-item">
         
          <h2 class="accordion-header" id="flush-headingOne">
            <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#flush-collapseOne" aria-expanded="false" aria-controls="flush-collapseOne">
              Dados cadastrais
              <div class="form-check form-switch end position-absolute sw">
                <!-- <label class="form-check-label" for="flexSwitchCheckDefault"></label>   -->
                <input class="form-check-input" type="checkbox" role="switch" id="flexSwitchCheckDefault3">
              </div>
            </button>

              
           
          </h2>

          <div id="flush-collapseOne" class="accordion-collapse collapse show" aria-labelledby="flush-headingOne" data-bs-parent="#accordionFlushExample">

            <div class="form-check form-switch">
              <label class="form-check-label" for="flexSwitchCheckDefault">Email</label>  
              <input class="form-check-input" type="checkbox" role="switch" id="flexSwitchCheckDefault1">
            </div>

            <div class="form-check form-switch">
              <label class="form-check-label" for="flexSwitchCheckDefault">Telefone</label>  
              <input class="form-check-input" type="checkbox" role="switch" id="flexSwitchCheckDefault2">
              
            </div>
            
          </div>
        </div>


        <div class="accordion-item">
          <h2 class="accordion-header" id="flush-headingTwo">
            <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#flush-collapseTwo" aria-expanded="false" aria-controls="flush-collapseTwo">
              Serviços acadêmicos

              <div class= "form-check form-switch end position-absolute sw">
              <input class="form-check-input" type="checkbox" role="switch" id="flexSwitchCheckDefault3">
            </div>
            </button>
          </h2>
          <div id="flush-collapseTwo" class="accordion-collapse collapse" aria-labelledby="flush-headingTwo" data-bs-parent="#accordionFlushExample">

            <div class="form-check form-switch">
              <label class="form-check-label" for="flexSwitchCheckDefault">Frequência Facial</label>  
              <input class="form-check-input" type="checkbox" role="switch" id="flexSwitchCheckDefault3">
            </div>

            <div class="form-check form-switch">
              <label class="form-check-label" for="flexSwitchCheckDefault">Atividade Complementar</label>  
              <input class="form-check-input" type="checkbox" role="switch" id="flexSwitchCheckDefault4">
              
            </div>
          </div>
        </div>


        <div class="accordion-item">
          <h2 class="accordion-header" id="flush-headingThree">
            <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#flush-collapseThree" aria-expanded="false" aria-controls="flush-collapseThree">
              Serviços financeiros
              <div class= "form-check form-switch end position-absolute sw">
              <input class="form-check-input" type="checkbox" role="switch" id="flexSwitchCheckDefault3">
            </div>
            </button>
          </h2>
          <div id="flush-collapseThree" class="accordion-collapse collapse" aria-labelledby="flush-headingThree" data-bs-parent="#accordionFlushExample">
            <div class="form-check form-switch">
              <label class="form-check-label" for="flexSwitchCheckDefault">xxx</label>  
              <input class="form-check-input" type="checkbox" role="switch" id="flexSwitchCheckDefault3">
            </div>

            <div class="form-check form-switch">
              <label class="form-check-label" for="flexSwitchCheckDefault">xxx</label>  
              <input class="form-check-input" type="checkbox" role="switch" id="flexSwitchCheckDefault4">
              
            </div>
          </div>
        </div>
      </div>
            

              
          
</div> 

        
    </section>
</template>
 
<style scoped>
.accordion-flush {

width: 70%;
margin-left: auto;
margin-right: auto;
border: 1px solid #ccc; /* Adiciona uma borda à div */
border-radius: 10px; /* Borda arredondada */
padding: 10px; /* Adiciona um preenchimento interno para que a borda não fique colada ao conteúdo */
font-weight: 200;
 

}


.form-check.form-switch {
display: flex;
justify-content: space-between;
align-items: center;
}

.form-check.form-switch .form-check-label {
order: 1; /* Altera a ordem do elemento */
font-family: 'Rubik';
font-weight: normal;


}

.form-check.form-switch .form-check-input {
order: 2; /* Altera a ordem do elemento */
margin-right: 10px;
}

.accordion-item .sw {right: 50px;}
.accordion-button {

font-weight: normal;
}


.accordion-header:hover {
background-color: #f0f0f0; /* Cor cinza claro */
}


.form-check:hover {

background-color: #f0f0f0; /* Cor cinza claro */

}

.form-switch {
padding: 10px;
}


</style>