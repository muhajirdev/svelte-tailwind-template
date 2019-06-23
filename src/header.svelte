<style lang="postcss">
  .test {
    /* Example tailwind @apply */
    @apply bg-blue-500 text-orange-100;
  }
  /* If you use vscode svelte extension. You'll red error.
     It will be solved after this PR merged
     https://github.com/UnwrittenFun/svelte-language-server/pull/20
   */
</style>

<header>
  <div class="test">test</div>
</header>
