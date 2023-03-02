<script lang="ts">
  import SidebarIcons from "./SidebarIcons.svelte";
</script>

<div
  class="fixed top-0 left-0 h-screen w-20 flex flex-col m-0 bg-gray-900 text-white shadow-lg"
>
  <SidebarIcons icon="fa-house" toolTip='house'/>
  <SidebarIcons icon="fa-paperclip" toolTip='bookmark'/>
  <SidebarIcons icon="fa-poo" toolTip='spam'/>
  <SidebarIcons icon="fa-cloud" toolTip='cloud'/>
</div>
