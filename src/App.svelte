<script>
  import { Button } from "sveltestrap";
  let bool = false;
</script>

<svelte:head>
  <link
    rel="stylesheet"
    href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" />
</svelte:head>

{#if bool}
  <Button color="primary" outline on:click={() => (bool = !bool)}>
    Hello World2!
  </Button>
{:else}
  <Button color="primary" outline on:click={() => (bool = !bool)}>
    Hello World2!
  </Button>
{/if}
