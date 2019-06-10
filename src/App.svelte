<svelte:options tag="my-custom-element" />
<script>
  export let name;
</script>

<div class="bg-red-500">
  <h1>Hello {name}!</h1>
</div>

<style>
  @import "/bundle.css";
</style>
