<script>
    // let formReg = {
    //     email: '',
    //     password: '',
    //     username: '',
    //     gender: true,
    // };
    let fromlog ={
        email: '',
        password: '',
    };

    const Handlelog = async () => {
        const response = await fetch('https://fdaf-83-234-174-21.ngrok-free.app/login', {
            method: 'POST',
            headers: {
                "Content-Type": "application/json",
                "Accept": "application/json",
                'Authorization':'111111'
            }, 
            body: JSON.stringify(fromlog),
        });
        if (response.ok) {
            alert('Турнир успешно создан!');
        } else {
            alert('Что-то пошло не так. Пожалуйста, попробуйте еще раз.');
        }
    };

function mytest(){
    console.log(fromlog)
}
</script>


<body>

    <div class="form">


        <form on:submit|preventDefault={Handlelog}>

        <img class="logo" src="logo_full.png" alt="logo">
        <p class="log">Логин</p>

        <input class="email" type="email" bind:value={fromlog.email}>

        <p class="pas">Пароль</p>
        <input class="password" type="password" bind:value={fromlog.password}>

        </form>


        <button class="input" type="submit" on:click = {mytest}> войти </button>
        <buttom class="reg"> <img class="image" src="reg.png" alt="favicon"/></buttom>
    </div>
</body>

<style>
    .input{
        
        
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