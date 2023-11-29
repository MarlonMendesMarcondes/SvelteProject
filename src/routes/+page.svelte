<script>
    import "../app.postcss";
    const lista = [
        'Joao',
        'Mateus',
        'Marcelo'
    ]
    for (let nome of lista){
        console.log(nome)
    }
</script>
<h1>Meu Site</h1>
<img src="MenccoLogo.png" alt="" style="width: 100px;">
{#each lista as nome}
<p>{nome}</p>
{/each}
<slot />

