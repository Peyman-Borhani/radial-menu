<script lang="ts">
	import '$/styles/index.scss';
	import '@tabler/icons-webfont/tabler-icons.min.css';
	interface Props {children?: import('svelte').Snippet}

	let { children }: Props = $props();

	export const csr = true;
	export const ssr = false;
</script>

{@render children?.()}
