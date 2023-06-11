<script lang="ts">
  import { M } from "svelte-motion";
</script>

<M.div initial="hidden" animate="show" variants={{hidden: {translateY: 200}, show: {translateY: 0}}}>
  Hi!
</M.div>
