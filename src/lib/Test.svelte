<script lang="ts">
  // This has a parse error, but it shouldn't
  const myAsyncFn = async (...args: unknown[]) => {
    console.log(args);
  };
</script>
