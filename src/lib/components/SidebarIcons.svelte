<script lang="ts">
  export let icon: string;
  export let toolTip: string = 'Tooltip';
</script>

<div class="sidebar-icon group">
  <i class={icon+' fa-sharp fa-solid fa-2x'}/>
  <span class="sidebar-tooltip group-hover:block">
    {toolTip}
  </span>
</div>
