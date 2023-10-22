<script>

</script>

<body>
    <div class="form">
        <img class="logo" src="logo_full.png" alt="logo">
        <p class="log">Логин</p>
        <input class="email" type="text">
        <p class="pas">Пароль</p>
        <input class="password" type="password">
        <button class="input"> <img class="image" src="input.png" alt="favicon"/></button>
        <buttom class="reg"> <img class="image" src="reg.png" alt="favicon"/></buttom>
    </div>
</body>

<style>
    .input{
        background-color:rgba(0,0,0,0.0);
        border: none;
        left: 11%;
        position: absolute;
        top: 500px;
    }
    .reg{
        background-color:rgba(0,0,0,0.0);
        border: none;
        left: 12%;
        position: absolute;
        top: 560px;
    }
    p{
        font-family:monospace;
        font-size: 1rem;
        font-weight: 400;
    }
    .log{
        left: 21%;
        position: absolute;
        top: 265px;
    }
    .pas{
        left: 21%;
        position: absolute;
        top: 345px;
    }
    .logo{
        position: absolute;
        left: 18%;
        top: 100px;
    }
    .email{
        position: absolute;
        left: 21%;
        top: 300px;
        padding: 0.375rem 0.75rem;
        font-family: monospace;
        font-size: 1rem;
        font-weight: 400;
        line-height: 1.5;
        color: #CCCCCC;
    }
    .password{
        position: absolute;
        left: 21%;
        top: 380px;
        padding: 0.375rem 0.75rem;
        font-family: monospace;
        font-size: 1rem;
        font-weight: 400;
        line-height: 1.5;
        color: #CCCCCC;
   
    }
    
    .form{
        position: relative;
        margin-left: auto;
        margin-right: auto;
        width: 369px;
        height: 708px;
        background-image: url("forms_sing_up.png");
    }
</style>