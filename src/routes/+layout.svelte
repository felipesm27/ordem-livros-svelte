<script lang="ts">
	import '../app.css';
	let { children } = $props();
</script>


<div class=" bg-black flex flex-col justify-center items-center text-white min-h-screen gap-5">

	{@render children()}
</div>

