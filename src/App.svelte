<script lang="ts">
  import { writable } from 'svelte/store'

  const store = writable([])
  $store.length // incorrect no-unsafe-member-access error
</script>
