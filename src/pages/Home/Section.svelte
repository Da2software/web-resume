<script>
    export let title;
</script>

<div class="cv-section">
  <h4 class="section-header">
    <span class="section-title">{title}</span>
  </h4>
  <div class="mx-1">
      <slot></slot>
  </div>
</div>

<style>
  .section-header {
    display: flex;
    width: 100%;
    border-bottom: 1px solid #525252;
  }
  .section-header .section-title {
    margin-top: -1rem;
    margin-left: auto;
    margin-right: auto;
    width: fit-content;
    height: fit-content;
    padding: 5px 10px;
    background-color: white;
  }
  .cv-section {
    width: 100%;
    display: grid;
    grid-template-columns: 100%;
    grid-template-rows: 20px auto;
  }
</style>
