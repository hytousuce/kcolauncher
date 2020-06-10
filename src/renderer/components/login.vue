<template>
    <div class="login_view">
        <div class="change_language">
            <span class="change_language_title">当前语言</span>
            <span class="change_language_lan">简体中文 - 中国大陆</span>
        </div>
        <div class="login_main">
            <div class="login_main_form">
                <div class="login_title">
                    Kcolauncher
                </div>

                
            </div>
            <div class="login_main_bg"></div>
        </div>
    </div>
</template>

<style>
    html, body {
        margin: 0;
        padding: 0;
        height: 100%;
        width: 100%;
    }

    #app {
        height: 100%;
        width: 100%;
    }

    .login_view {
        height: 100%;
        width: 100%;
        background-image: url("../assets/bg-wool-dark.png");
        background-repeat: repeat;
        background-size: initial;
        display: flex;
        justify-content: center;
        align-items: center;
    }

    .change_language {
        display: block;
        position: absolute;
        right: 0;
        top: 0;
        border-radius: 0 0 0 5px;
        box-shadow: 0 5px 10px rgb(0, 0, 0);
        background-color: rgb(49, 156, 97);
        overflow: hidden;
        color: lightgrey;
        font-size: 0.8em;
    }

    .change_language span {
        display: inline-block;
        height: 100%;
        padding: 5px 10px;
    }
    .change_language_title {
        background-color: rgb(47, 79, 79);
    }

    .login_main {
        position: relative;
        height: 400px;
        width: 300px;
        background-color: rgb(29, 48, 48);
        margin: 0 auto;
        border-radius: 5px;
        border: 2px solid rgb(24, 41, 41);
        box-shadow: 0 5px 10px rgb(0, 0, 0);
        overflow: hidden;
        color: whitesmoke;
    }

    .login_main_form {
        height: 70%;
        width: 100%;
        display: flex;
        justify-content: center;
        align-items: center;
    }
    .login_main_bg{
        position: absolute;
        height: 30%;
        width: 100%;
        bottom: 0;
        background-image: url("../assets/login-main-bg.png");
        background-size: cover;
        background-position: center;
    }

    .login_title {
        font-weight: 900;
        font-size: 1.5em;
    }
</style>

<script>
export default {
    
}
</script>