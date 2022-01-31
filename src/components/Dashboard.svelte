<script>
    let isShown = false;

    const changeIsShown = () => {
        isShown = !isShown;
    }
    
</script>
<div>
    {#if isShown}
    
    <span>Hello</span>


    {/if}
    <button class="btn btn-accent btn-sm" on:click={changeIsShown}>Click On me</button>
</div>