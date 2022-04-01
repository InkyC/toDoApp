<script>
    export let text;
    export let checked;
    export let removeItem;
    export let toggleDone;
</script>

<li>
    <input bind:checked={checked} on:change={toggleDone} type="checkbox"> 
    <span class:checked={checked}>{text}</span>
    <button class="btn" type="button" on:click={removeItem}>x</button>
 
</li>

<style>

    :hover{

    text-decoration: line-through;

    }

    .checked {
        text-decoration: line-through;
        color: rgb(0, 0, 0);
    }
    .btn {

    color: brown;

    }
</style>