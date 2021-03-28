<script>
  import Obj from './Obj.svelte';
  import { fade } from 'svelte/transition';

  //export let objectId = null;
  export let params = {};
</script>

<div in:fade>
  <Obj objectId={params.objectId} />
</div>
