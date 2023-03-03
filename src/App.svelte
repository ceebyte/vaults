<script>
  import Router from 'svelte-spa-router'
  import Links from './lib/Links.svelte';
  import Counter from './lib/Counter.svelte'
    import PinLock from './lib/PinLock.svelte';
    import Over from './lib/Over.svelte';

  const routes = {
    '/counters': Counter,
    '/pinlock': PinLock,
    '/links': Links,
    '/over': Over,
  }
</script>

<Router {routes}/>

<main>
  <div class="card">
    LANDING
    
  </div>
  <Links/>
</main>


