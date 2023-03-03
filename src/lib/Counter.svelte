<script>
  import Links from "./Links.svelte";

  let count = 0
  const increment = () => {
    count += 1
  }
</script>

<h1>/COUNTER</h1>

<Links/>

<button on:click={increment}>
  count is {count}
</button>
