
<script>
  import CharityList from "../components/CharityList.svelte";
	import Footer from "../components/Footer.svelte";
	import Header from "../components/Header.svelte";
	import Promo from "../components/Promo.svelte";
	import Welcome from "../components/Welcome.svelte";
  import { charities } from "../data/charities.js";
</script>

<Header />
<Welcome />
<CharityList {charities} />
<Promo />
<Footer />
