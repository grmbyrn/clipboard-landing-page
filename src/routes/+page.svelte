<script lang="ts">
    import History from "$lib/components/History.svelte";
    import Snippets from "$lib/components/Snippets.svelte";
    import Access from "$lib/components/Access.svelte";
    import Supercharge from "$lib/components/Supercharge.svelte";
    import Clipboard from "$lib/components/Clipboard.svelte";
    import Footer from "$lib/components/Footer.svelte";
</script>

<div class="container">
    <History />
    <Snippets />
    <Access />
    <Supercharge />
    <Clipboard />
    <Footer />
</div>

<style>
    .container {
		width: 23.438rem;
		background-color: #ffffff;
		display: block;
		margin-left: auto;
		margin-right: auto;
        font-family: "Bai Jamjuree", sans-serif;
        padding-inline: 2rem;
	}
</style>