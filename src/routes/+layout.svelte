<style>
    :root{
        color: red;
    }
</style>

<script>
    import '../main.css';
    import Header from '$lib/header.svelte';
    import Navigation from '$lib/navigation.svelte'; //importing a component
    import Footer from '../lib/footer.svelte';
    import Tags from '../lib/tags.svelte';
</script>


<Header /> 
<Navigation />

<div> 
    <slot /> <!-- page specific content -->
</div>

<Tags />

<Footer />
