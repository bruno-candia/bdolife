<script>
  import Button from '../../components/Button/Button.svelte';
  import '../horse/style.scss';
  import {cavalo} from '../../assets/volta-rapida.png';
</script> 

<section>
    <h1 class='title'>TIER</h1>
    <div class='tiers'>
      {#each [8,7,6,5] as j}
        <Button tier={j} />
      {/each}
    </div>
    <div class='content'>
      <div class='horse-content'>
        <img src={cavalo} alt="Cavalo de raça 8A">
      </div>
      <div>

      </div>
    </div>
</section>