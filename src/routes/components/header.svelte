<script lang="ts">
	import Toggle from './toggle.svelte'
	import * as config from '$lib/config'
</script>

<div class="navbar bg-base-100">
	<div class="navbar-start">
		<a href="/" class="title">
			<b>{config.title}</b>
		</a>
	</div>
	<div class="navbar-center">
		<ul class="links">
			<li>
				<a href="/about">About</a>
			</li>
			<li>
				<a href="/contact">Contact</a>
			</li>
			<li>
				<a href="/rss.xml" target="_blank">RSS</a>
			</li>
		</ul>
	</div>
	<div class="navbar-end">
		<a class="" href="https://github.com/sveltejs/svelte" target="_blank"> github</a>
		<Toggle />
	</div>
</div>

<style>
</style>
