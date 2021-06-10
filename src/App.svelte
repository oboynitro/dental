<script>
  import { Router, Route, Link, useLocation } from "svelte-navigator";
  import Home from "./routes/Home.svelte";
  import Contact from "./routes/Contact.svelte";
  import Gallery from "./routes/Gallery.svelte";
  import Feature from "./routes/Feature.svelte";
import Header from "./components/Header.svelte";
import Footer from "./components/Footer.svelte";
  export let url = ""; //This property is necessary declare to avoid ignore the Router
</script>

<Router url="{url}">
    <Header />
    <div>
        <Route path="/" component={Home} />
        <Route path="gallery" component={Gallery} />
        <Route path="contact" component={Contact} />
        <Route path="features" component={Feature} />
    </div>
    <Footer />
</Router>