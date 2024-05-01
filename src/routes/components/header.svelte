<script lang="ts">
	import Toggle from './toggle.svelte'
	import * as config from '$lib/config'
</script>

<header>
	<nav>
		<a href="/" class="title">
			<b>{config.title}</b>
		</a>

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

		<Toggle />
	</nav>
</header>

<style>
</style>
