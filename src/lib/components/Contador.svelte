<script>
    let contador = 0;
    function ejecutar(){
        contador++
    }
</script>
<p>contador : {contador}</p>
<button class="" on:click={ejecutar}>Contar</button>