<script>
  import viteLogo from '/vite.svg'
  import Authbox from './routes/auth.svelte'
  import Options from './routes/options.svelte'
  import Add from './routes/add.svelte'
  import Test from './components/tag.svelte'
  import {Router,Link,Route} from "svelte-routing";
  export let url = "";
</script>


<Router>
    <Route path="/" component={Authbox}></Route>
    <Route path="/options" component={Options}></Route>
    <Route path="/add" component={Add}></Route>
    <Route path="/tests" component={Test}></Route>
</Router>

 
