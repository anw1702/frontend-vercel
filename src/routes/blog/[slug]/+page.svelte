<script lang="ts">
  export let data;
</script>

<p class="font-bold text-center">{data.content}</p>

<div>
  {#each data.names as { name } (id)}
    <div class="font-semibold">{name}</div>
  {/each}
</div>
