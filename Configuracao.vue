<script setup lang="ts">
 
</script>
 
<template>
 <section class="py-5 mt-5">
        <div class="container py-4 py-xl-5">
           
            <ol class="breadcrumb mb-5">
                <li class="breadcrumb-item"><router-link to="/"><span>Home</span></router-link></li>
                <li class="breadcrumb-item active"><span>Configurações</span></li>
            </ol>
           
            <h1 class="display-6 fw-bold">Configurações</h1>
 
            <div class="row gy-4 gy-md-0">

                <nav class="navbar navbar-light  justify-content-between" id="teste">
            <a class="navbar-brand" id="notif">Notificações de atividades</a>

            <div class="form-check form-switch">
                <input class="form-check-input" type="checkbox" role="switch" id="flexSwitchCheckDefault">
                <label class="form-check-label menu" for="flexSwitchCheckDefault">Habilitar</label>
              </div>

          </nav>
            </div>
        </div>
    </section>
</template>
 
<style scoped>

#habilitar{
  margin-right: 10px;
}


.footer {
  position: fixed;
  bottom: 0;
  width: 100%;
}


#notif {
        
  margin-left: 20px;
  font-size: 16px;
}


 

#teste {
  border: 1px solid #ccc;
}

.menu {
  color: #198754;
  margin-right: 10px;
}

</style>