<script>
    let count = 0;
    export let demo;
    function subtract() {
        count--;
    }

    function add() {
        count++;
    }
</script>

<div>
      Svelte Count: {count} {demo}
      <br />
      <button on:click={subtract}>-</button>
      <button on:click={add}>+</button>
</div>