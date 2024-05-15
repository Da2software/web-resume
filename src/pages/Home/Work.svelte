<script>
  export let Role;
  export let StarDate;
  export let EndDate;
  export let Company;
</script>

<div class="cv-work">
  <div class="work-header">
    <h5 class="work-role mb-1">
      {Role}, {#if StarDate && EndDate}
        <span class="dates">{StarDate} - {EndDate}</span>{/if}
    </h5>
    {#if Company}<h6 class="work-company my-1">{Company}</h6>{/if}
  </div>
  <slot></slot>
</div>

<style>
  .cv-work {
    width: 100%;
    display: grid;
    grid-template-rows: auto auto;
    grid-template-columns: auto;
  }
  .cv-work .work-header {
    height: fit-content;
  }
  .cv-work .work-company,
  .cv-work .work-role {
    font-size: 14px;
  }
  .cv-work .work-header .dates {
    color: #535353;
    font-weight: lighter;
  }
</style>
