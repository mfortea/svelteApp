<script>
  import { Link } from "svelte-routing";
</script>

<style>
    div { border: solid 1px black;}
</style>
    
<nav>        
  <Link to="/">Inicio</Link>
  <Link to="/articulos">Artículos</Link>
  <Link to="/clientes">Clientes</Link>
</nav>