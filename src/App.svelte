<script>
import { Router, Route } from "svelte-navigator";
import Home from "./routes/Home.svelte";

</script>

<Router>
	<Route path="/">
		<Home />
	</Route>
</Router>