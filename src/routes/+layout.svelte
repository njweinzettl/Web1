<style>
    :root{
        color: red;
    }
</style>

<script>
    import Navigation from '$lib/navigation.svelte'; //importing a component
    import Footer from '../lib/footer.svelte';
</script>

<Navigation /> 
<!-- we put the nav into a component because you write it once and can use it in several places -->

write common 
<slot /> <!-- page specific content -->
<br/>
And I am some common footer stuff

<Footer />
