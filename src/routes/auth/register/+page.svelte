<script></script>

<form action=POST>
    <label for="SIGN-user">Username:</label>
    <input id="SIGN-user" type="text" name="username" placeholder="Nombre de usuario"/>
    <label for="SIGN-password">Contrasena:</label>
    <input id="SIGN-password" type="text" name="contrasena" placeholder="Contrasena"/>
    <button type="submit" id="send-btn">Crear cuenta</button>
</form>

<style>
    form {
        font-size: 2.4em;
        margin: 4em;
        color: #813408;
        text-align: center;
    }

    #send-btn {
        background-color: #676127;
        color: #F6F0E2;
        padding: 0.2em 0.4em;
        display: block;
        margin: 0.4em auto;
    }

    input {
        font-size: 1em;
    }

    label  {
        display: block;
    }
</style>