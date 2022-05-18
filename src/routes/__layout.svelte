<script>
  import "../app.scss";
  import Nav from "../components/Nav/Nav.svelte";
</script>

<svelte:head>
  <title>bdolife.net</title>
</svelte:head>

<div class='container'>
  <Nav/>
  <slot/>
</div>
