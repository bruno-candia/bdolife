<script>
  import "../app.css";
  import Nav from "../components/Nav/Nav.svelte";
</script>

<svelte:head>
  <title>bdolife.net</title>
</svelte:head>

<div class='mx-6 my-5'>
  <Nav/>
  <slot/>
</div>
