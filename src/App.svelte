<script>
  import Icon from "svelte-awesome";
  import { camera } from "svelte-awesome/icons";
  import Footer from "./components/Footer.svelte";
</script>

<section class="hero">
  <div class="hero-body">
    <p class="title">Hello World!</p>
    <p class="subtitle">Svelte Sample</p>
  </div>
</section>
<div class="section">
  <div class="container">
    <div>
      <Icon data={camera} scale="1" />
      Body Text.
    </div>
  </div>
</div>
<Footer name="@cympfh" />

<style global lang="scss">
  @import "main.scss";
</style>
