<script>

</script>


<template>
    <h1 class="self-center">Participantes do NTI</h1>

    <div style="padding: 30px;" class="flex-row self-center space-x-8 items-center">
      <ul>
	<li>
	  <h2 class="nome">$_PARTICIPANTE1</h2>
	  <p> $_FUNÇÃO1</p>
	</li>
	<li>
	  <h2 class="nome"> $_PARTICIPANTE2</h2>
	  <p>$_FUNÇÃO2</p>
	</li>
	<li><h2 class="nome">$_PARTICIPANTE3</h2>
	  <p>$_FUNÇÃO3</p>
	</li>

	<li>
	  <h2 class="nome">$_PARTICIPANTE4</h2>
	  <p>$_FUNÇÃO4</p>
	</li>
      </ul>
      <img src="../assets/sao_jose.png">
    </div>
</template>


<style scoped>

.nome{
    @apply font-semibold underline
}
  
@media(min-width: 1024px){
    .about{
	 min-height: 100vh;
	 display: flex;
	 align-items: center;
    }
}

  
img{
    display: block;
    margin: auto;
    width: 40%;
    heigth: 300px;
}
</style>


