<script>
    let count = $state(0);
    let randomtextinput = $state("")
    const whenButtonClicked = () => {
        console.log("smth was pressed");
        count += 1;
    }
</script>

<h1>WEBPAGE</h1>

<button onclick={whenButtonClicked}>click</button>
{count}
<button onclick={() => count -= 1}>decrease</button>

<input type="text" bind:value={randomtextinput} />

{randomtextinput}

// Run WEBPAGE: npm run dev -- --open
