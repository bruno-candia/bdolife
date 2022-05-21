<script>
  import Button from '../../components/Button/Button.svelte';
  import '../horse/style.scss';
</script> 

<section class='tier'>
    <h1 class='title'>TIER</h1>
    <div class='tiers'>
      {#each [8,7,6,5] as j}
        <Button tier={j} />
      {/each}
    </div>
    <div class='content'>
      <div class='horse-content'>
        <img src='/images/8C.png' alt="Cavalo de raça 8A">
      </div>
      <div>
        <div>
          <h2>Nível</h2>
          <input type="number">
          <h2>Habilidade</h2>
          <input type="number">
          <div>
            <h2>Uso de Cupom</h2>
            <img src='/images/forte-coice.png' alt="Cavalo de raça 8A">
            <span>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sapien sit ligula vulputate mi cras nisl dapibus facilisis dolor.</span>
          </div>
          <div>
            <h2>Ordem de Troca de Habilidade</h2>
            <span>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sapien sit ligula vulputate mi cras nisl dapibus facilisis dolor.</span>
          </div>

        </div>

      </div>
    </div>
</section>