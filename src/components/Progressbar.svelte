<script>
    export let progress = 50;
    let height = "30px";
    let width = "100%";
</script>

<div class="progressbar" style="height: {height}; width: {width}">
    <div class="progress-fill" style="width: {progress}%;" />
</div>

<style>
    .progressbar {
        padding: 0;
        margin: 0;
        overflow: hidden;
        background-color: var(--background-light);
        border: 2px solid var(--primary-light);
    }
    .progressbar .progress-fill {
        height: inherit;
        background-color: var(--primary-light);
    }
</style>
