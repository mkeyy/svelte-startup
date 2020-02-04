<script>
    export let svgSRC;
    export let classes;

    const svg = svgSRC.replace('<svg', '<svg class="' + classes + '"');
</script>

{@html svg}