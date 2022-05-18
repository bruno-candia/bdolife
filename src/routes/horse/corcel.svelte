<script>
  import Button from '../../components/Button/Button.svelte';
  import '../horse/style.scss';
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
        <!-- <img src='../../../static/8C.png' alt="Cavalo de raça 8A"> -->
      </div>
      <div>

      </div>
    </div>
</section>