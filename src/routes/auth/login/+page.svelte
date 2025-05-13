<script>
    let isHidden = true

    function changeVisibility() {
        if (isHidden) {
            const passwordInput = document.getElementById("LOGIN-password")
            passwordInput.setAttribute("type", "text")
            isHidden = false
        } else {
            const passwordInput = document.getElementById("LOGIN-password")
            passwordInput.setAttribute("type", "password")
            isHidden = true
        }
    }

</script>

<form action="POST">
    <label for="LOGIN-user">Username:</label>
    <input id="LOGIN-user" type="text" name="username" placeholder="Nombre de usuario"/>
    
    <label for="LOGIN-password">Contrasena:</label>
    <input id="LOGIN-password" type="password" name="contrasena" placeholder="Contrasena"/>
    
    <button id="visibility-btn" on:click="{changeVisibility}" type="button">👁️‍🗨️</button>
    <button type="submit" id="send-btn">Iniciar sesion</button>
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