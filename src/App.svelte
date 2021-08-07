<script>
	import { Router, Link, Route } from "yrv";
	import Home from "./home.svelte";

  
	export let url = "";
  </script>
  
  <Router url="{url}">
	
	  <Link to="/">
		<Link to="/user"></Link>
	</Link>
	  
	 
	
	
	  <Route path="/"><Home /></Route>
	
  </Router>