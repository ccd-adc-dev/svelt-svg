<script>
  import Shape from './Shape.svelte'
  export let w
  export let h
  export let pointsArray
</script>

<h1>Playground</h1>
<svg width={w} height={h}>
  {#each pointsArray as points}
    <Shape points={points}/>
  {/each}
</svg>