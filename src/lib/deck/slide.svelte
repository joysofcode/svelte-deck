<script lang="ts">
	export let id: string | null = null
	export let animate = false
	export let restart = false
</script>

<section
	data-auto-animate-id={id}
	data-auto-animate={animate || null}
	data-auto-animate-restart={restart || null}
>
	<slot />
</section>
