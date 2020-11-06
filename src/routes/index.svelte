<script>
  import News from "../components/News.svelte";
  import Footer from "../components/Footer.svelte";
  import Header from "../components/Header.svelte";
  import HeroSlider from "../components/HeroSlider.svelte";
  import onMount from 'svelte';

</script>

<Header indexClass="active" page="/" />
<HeroSlider />
<News />
<Footer />
