<script>
	export let color = undefined
	export let size = 15
	export let width = undefined
	export let height = undefined
</script>

<svg
	{color}
	width={width ?? size}
	height={height ?? size}
	viewBox="0 0 24 24"
	stroke-width="1.5"
	stroke="currentColor"
	fill="none"
	stroke-linecap="round"
	stroke-linejoin="round"
	aria-label="search"
>
	<path stroke="none" d="M0 0h24v24H0z" fill="none" />
	<circle cx="10" cy="10" r="7" />
	<line x1="21" y1="21" x2="15" y2="15" />
</svg>
