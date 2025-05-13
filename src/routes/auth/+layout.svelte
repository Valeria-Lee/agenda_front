<script>
    import Footer from "../../lib/components/Footer.svelte"
    let {name, children} = $props();
</script>

<a id="home-btn" href="/">GO HOME 🏠︎</a>
    <h3>{name}</h3>
    {@render children()}
<Footer/>

<style>
    #home-btn {
        padding: 2vh;
        font-size: 2em;
        background-color: #676127;
        text-decoration: underline;
        color:#CFC4B2;
        display: block;
    }
</style>
