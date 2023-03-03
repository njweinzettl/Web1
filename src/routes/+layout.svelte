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
</script>

<Navigation /> 
<!-- we put the nav into a component because you write it once and can use it in several places -->

<Header /> 

<div> 
    <slot /> <!-- page specific content -->
</div>

<Footer />
