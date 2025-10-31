<script lang="ts">
	import '$/styles/index.scss';
	import '@tabler/icons-webfont/dist/tabler-icons.min.css';
	interface Props {children?: import('svelte').Snippet}

	let { children }: Props = $props();

	export const  ssr  = false;	
    //export const csr =true;  //Deprecated
</script>

{@render children?.()}
