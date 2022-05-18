<script>
  import logoBdolife from '../../assets/logo-bdolife.svg';
  import { MenuIcon } from 'svelte-feather-icons'
  import '../Nav/style.css';
</script>

<header class='header'>
  <button class='menu-button'>
    <MenuIcon size='32' />
  </button>
  <div class='logo'>
    <img src={logoBdolife} alt="Logo Bdolife">
  </div>
</header>
