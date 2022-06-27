<script>
    import {autoselect} from "$lib/index";

    let example = "Hello World!";
</script>

<h1>svelte-autoselect</h1>

<p>Without autoselect:</p>
<input type="text" bind:value={example}>

<p>With autoselect:</p>
<input type="text" bind:value={example} use:autoselect>
