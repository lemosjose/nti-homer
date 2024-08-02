<script setup>


</script>

<template>
<div style="padding: 30px;" class="self-center flex-column space-x-8 items-center">
  <ul class="flex-row">
    <li> <a href="192.168.1.4" class="link" > Octoprint  (Anet A8) </a></li>
    <li><RouterLink class="link" style="background-color: red" to="/nti" >Estagiários Resposáveis </RouterLink></li>
  </ul>
    <img class="relative" style="display: block; margin: auto;" src="../assets/sao_bento.png" />
    <p class=" self-center text-3xl central_texto">
      Central de comando 
    </p>

    <p class="self-center homer_text">
      NTI-HOMER
    </p>
</div>

  
</template>

<style scoped>

.link{
    @apply text-white underline font-semibold;
}
 
.central_texto{
    color: black;
    font-weight: 600;
 }

 @media(min-width: 1024px){
     .about{
	 min-height: 100vh;
	 display: flex;
	 align-items: center;
     }
}

img{ 
  width: 40%;
  height: 300px;
  display: block;
  margin: auto;
}

</style>
