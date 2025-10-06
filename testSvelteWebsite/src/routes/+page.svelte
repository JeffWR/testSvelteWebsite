<script>
    let count = $state(0);
    let randomtextinput = $state("")
    const whenButtonClicked = () => {
        console.log("smth was pressed");
        count += 1;
    }
</script>

<h1>Welcome to my Project</h1>

<button onclick={whenButtonClicked}>click</button>
{count}

<input type="text" bind:value={randomtextinput} />
{randomtextinput}