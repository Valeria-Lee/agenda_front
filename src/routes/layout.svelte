<script>
    import Footer from '../lib/components/Footer.svelte'
    let { name, children }  = $props()
    let username = "valeria" // jalarlo del inicio de usuario, poner un valor por defecto
</script>

<div id="section">
    <div>
        <a href="/" id="homeBtn">agenda</a>
        <h2>⊹ {name} ⊹</h2>
    </div>
    {@render children()}
</div>

<Footer/>

<style>
    @import url('https://fonts.googleapis.com/css2?family=Beth+Ellen&display=swap');

    #section {
        text-align: center;
        background-color: #935627;
        color: #CFC4B2;
        padding: 2vh;
    }

    #homeBtn {
        font-family: "Beth Ellen", cursive;
        font-size: 1.6em;
        margin: 2.4em;
        color: #F6F0E2;
    }

    #homeBtn:hover {
        color: #411B1A;
    }
</style>