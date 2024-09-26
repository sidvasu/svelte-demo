<script>
    let count = 0;
</script>

<button on:click = {() => (count += 1)}> Increment </button>
<div>
    inc: {count}
</div>