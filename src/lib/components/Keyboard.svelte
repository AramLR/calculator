<script lang='ts'>
  const keyboard = [
    '7','8','9', '+', '^',
    '4','5','6', '-', '(',
    '1','2','3', '*', ')',
    '.','0','+/-', '/', '='
  ]
</script>

<div class="grid grid-cols-5 grid-rows-4 h-[90vh]">
  {#each keyboard as key}
    <button class="btn rounded-none w-full h-full text-2xl">{key}</button>
  {/each}
</div>