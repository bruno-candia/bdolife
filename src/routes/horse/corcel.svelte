<script>
  import Button from '../../components/Button/Button.svelte';
</script> 

<section>
    <h2 class='flex text-center  text-white font-bold text-xl items-center justify-center'>TIER</h2>
    <div class='flex gap-6 justify-center'>
      {#each [8,7,6,5] as j}
        <Button tier={j} />
      {/each}
    </div>
</section>