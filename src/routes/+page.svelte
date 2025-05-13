<script>
    import Header from '../lib/components/Header.svelte'
    import Footer from '../lib/components/Footer.svelte';
</script>

<div id="container">
    <Header/>
    <div id="landing-img">
        <img src="reading_gif.gif" alt="gif de leer un libro">
    </div>
    <div id="nav-btns">
        <a href="events">eventos</a>
        <a href="contacts">contactos</a>
    </div>
</div>

<Footer/>

<style>
    :global(*) {
        padding: 0;
        margin: 0;
        box-sizing: border-box;
    }

    #container {
        display: flex;
        justify-content: center;
        align-items: center;
        text-align: center;
        flex-direction: column;
        width: 100%;
        height: 92vh;
        background-color: #FBF8E9;
    }

    #landing-img {
        width: 60vh;
        max-width: 100%;
        display: flex;
        justify-content: center;
        align-items: center;
    }

    #landing-img img {
        width: 100%;
        height: auto;
        object-fit: contain;
    }

    #nav-btns {
        margin-top:2vh;
    }

    #nav-btns > * {
        font-size: 4.8vh;
        text-decoration: none;
        background-color: #935627;
        margin: 3vw;
        padding: 0% 1vh;
        border-radius: 1.2vh;
        color:#141414;
        display: inline-block;
    }

    #nav-btns > *:hover {
        transform: rotate(15deg);
        background-color: #CFC4B2;
        box-shadow: #935627 1vh 2vh;
        margin: 3vw;
    }

</style>