<script>
  import HorseCarrossel from "../../components/HorseCarrossel/HorseCarrossel.svelte";
  import Button from "../../components/Button/Button.svelte";
  import "../horse/style.scss";
</script>

<section class="tier">
  <h1 class="title">TIER</h1>
  <div class="tiers">
    {#each [5, 6, 7, 8] as j}
      <Button tier={j} />
    {/each}
  </div>
  <div class="content">
    <HorseCarrossel />
    <div>
      <div>
        <h2>Nível</h2>
        <input type="number" />
        <h2>Habilidade</h2>
        <input type="number" />
        <div>
          <h2>Uso de Cupom</h2>
          <img src="/images/forte-coice.png" alt="Cavalo de raça 8A" />
          <span
            >Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sapien sit
            ligula vulputate mi cras nisl dapibus facilisis dolor.</span
          >
        </div>
        <div>
          <h2>Ordem de Troca de Habilidade</h2>
          <span
            >Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sapien sit
            ligula vulputate mi cras nisl dapibus facilisis dolor.</span
          >
        </div>
      </div>
    </div>
  </div>
</section>
