<script lang="ts">
	import Adminlist from '$lib/mv/adminlist.svelte';
	export let data;
</script>

<Adminlist
	title="Számlák"
	type="számla"
	{data}
	editdes="számlájának"
	extraText="Összeg"
	am={data.layout.am}
	tools={['edit']}
/>
