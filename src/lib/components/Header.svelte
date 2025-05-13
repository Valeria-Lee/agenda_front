<script></script>


<div id="sign-options">
    <a href="/auth/login">INICIAR SESION</a>
    <img src="book_icon.png" alt="icono de libro" id="icono"/>
    <a href="/auth/register">REGISTRARSE</a>
</div>
<header>
    <a href="./">Agenda</a>
</header>

<style>
    @import url('https://fonts.googleapis.com/css2?family=Beth+Ellen&display=swap');

    * {
        display: flex;
    }

    header > * {
        z-index: 10;
        font-family: "Beth Ellen", cursive;
        font-size: 10vh;
        text-decoration: none;
        text-align: center;
        color: #302A26;
        padding: 0;
    }

    #sign-options {
        font-family: "Fustat", sans-serif;
        font-size: 4vh;
    }

    #sign-options > a {
        margin: 0vh 2vh;
        color: #676127;
        padding: 0.2em;
    }

    #icono {
        width: 1.2em;
        height: 1.2em;
    }

    header {
        margin-top: none;
    }

</style>