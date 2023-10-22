<script>
let nameTourney = "Турнир А4. лига 350-400"
let nameTeam = "Булочки с корицией 2"
let size = 0
let status ="Cкоро пройдет"
let teamCount = 0
let username = "Иванов Иван Иванович"
let ID="1397304"
let user1name = "Тюлеев Мерген"
let user2name = "Фисенко Александр"
</script>
<header>
    <a href="" ><img class="logo" src="logo.png" alt="logo"/></a>
    <a href="" ><img class="lk" src="lk.png" alt="lk"/></a>
</header>

<body>
 
<div class="first_block">
    <div class="text_first">
    <p1>Команды
       <br/>{username}
    </p1>
    
    </div>
    
        <a class="pluse" href="" ><img class="plusImg" src="plus3.png" alt="logo"/></a>
    
</div>   

<div class="group">

<div class="block">
    <b>Турнир: {nameTourney}</b>
    <p><b>Название команды:</b> {nameTeam}</p>
    <p><b>Капитан:</b> {user1name}</p>
    <p><b>Участник:</b> {user2name}</p>
    <div class="st"><p1>ID команды: {ID}</p1></div>
</div>

<div class="block">
    <b>Турнир: Турнир А6. лига 500-550</b>
    <p><b>Название команды:</b><br/>MLS</p>
    <p><b>Капитан:</b> {user1name}</p>
    <p><b>Участник:</b> Полянская Юлия</p>
    <div class="st"><p1>ID команды: 3456728</p1></div>
</div>

<div class="block">
    <b>Турнир: Турнир А9. лига 700-800</b>
    <p><b>Название команды:</b> Forceful</p>
    <p><b>Капитан:</b> {user1name}</p>
    <p><b>Участник:</b> Безруков Михаил</p>
    <div class="st"><p1>ID команды: 76830498</p1></div>
</div>







</div>

</body>

<style>
header{
    width: 100%;
    height: 50px;
    position: relative;
    padding-top: 10px;
    background-color: #FFDD2D;
    border-bottom: 3px solid;
}
body{
    width: 100%;
    height: auto;
    display:inline-block;
    margin:  0 auto;
    background-color: black;
    
}




.logo{
        
        position: absolute;
        width: 12%;
        left: 10%;
    }
.lk{
    margin-top: 4px;
    position: absolute;
    width: 2.5%;
    right: 10%;
    }



.group{
    padding-left: 7%;
    background-color: white;
    border-radius: 40px 40px 0px 0px;
}
b{
    font-family:monospace;
        font-size: 20pt;
        
}
p{
        font-family:monospace;
        font-size: 20pt;
        font-weight: 400;
}
p1{
    font-family:monospace;
    font-size: 18pt;
    font-weight: 400;
    color: white;
    background-color: black;
    padding: 5px;
    border-radius: 20px;
    
}
.st{
    
    width: auto;

}
.block{
    border-radius: 20px;
    padding: 20px;
    display: inline-block;
    width: 22%;
    height: auto;
    margin: 40px;
    background-color: #FFDD2D; 
}
.first_block{
    padding-top: 5%;
    height: 400px;
    background-color: black;
    position: relative;
}

.pluse{
    
    position: absolute;
    right: 10%;
}
.pluseImg{
    width: 10px;
}
.text_first{
    position: absolute;
    left: 10%;
}



</style>