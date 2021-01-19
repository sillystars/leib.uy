<script>
  import { Router, Link, Route } from "svelte-routing";

  import Home from "./routes/Home.svelte";
  import About from "./routes/About.svelte";
  import Contact from "./routes/Contact.svelte";
  import Works from "./routes/Works.svelte";

  export let url = "";
</script>

<Router url="{url}">
  <div>
    <Route path="contact" component="{Contact}" />
    <Route path="works" component="{Works}" />
    <Route path="about" component="{About}" />
    <Route path="/"><Home /></Route>
  </div>
</Router>