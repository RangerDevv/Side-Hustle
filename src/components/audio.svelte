<script>

    export let musicSource = String;

    function Slider() {

    }

</script>

<main>
    <audio src={musicSource}></audio>
    <div>
        <input type="range" step="1" class="w-96" on:drag={Slider}>
    </div>
</main>