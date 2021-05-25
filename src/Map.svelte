<script>
    import { onMount } from "svelte"
    let canvas;

    onMount(() => {
        let ctx = canvas.getContext("2d");
        function draw() {
            ctx.beginPath();
            ctx.arc(100, 75, 50, 0, 2 * Math.PI);
            ctx.stroke(); 
        }
        draw();
    })
</script>

<div class="map-wrapper">
    <canvas bind:this={canvas}/>
</div>

<style lang="scss">
    .map-wrapper {
        display: flex;
        border: 1px solid red;

        canvas {
            max-width: 95%;
            width: 100vw;
            height: 80vh;
            margin: 0 auto;
            border: 1px dotted black;
        }
    }

    @media screen and (min-width: 676px) {
        .map-wrapper {
            canvas {
                max-width: 1280px;
            }
        }
    }
</style>