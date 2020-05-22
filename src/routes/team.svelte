<script>
  import Footer from "../components/Footer.svelte";
  import Header from "../components/Header.svelte";
  import Team from "../components/Team.svelte";
</script>

<div class="site-wrapper clearfix">
  <div class="site-overlay" />
  <div id="root">
    <div id="home">
      <Header teamClass = "active" />
      <Team />
      <Footer />
    </div>
  </div>
</div>