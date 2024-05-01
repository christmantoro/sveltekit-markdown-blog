<script lang="ts">
	import * as config from '$lib/config'
</script>

<footer class="flex flex-1 flex-col items-center justify-center">
	<p>{config.title} &copy {new Date().getFullYear()}</p>
</footer>

<style>
	footer {
		padding-block: var(--size-7);
		border-top: 1px solid var(--border);
	}

	p {
		color: var(--text-2);
	}
</style>
