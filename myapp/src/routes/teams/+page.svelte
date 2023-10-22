<script>
    let name = "Турнир 1"
    let size = 0
    let status ="Cкоро пройдет"
    let teamCount = 0
    </script>
    <header>
        <a href="" ><img class="logo" src="logo.png" alt="logo"/></a>
        <a href="" ><img class="lk" src="lk.png" alt="lk"/></a>
    </header>
    
    <body>
    <div class="group">
    
    <div class="block">
        <b>Имя: {name}</b>
        <p>Количество команд: {teamCount}/{size}</p>
        <div class="st"><p1>Статус: {status}</p1></div>
    </div>
    
    <div class="block">
        <b>Имя: {name}</b>
        <p>Количество команд: {teamCount}/{size}</p>
        <div class="st"><p1>Статус: {status}</p1></div>
    </div>
    
    <div class="block">
        <b>Имя: {name}</b>
        <p>Количество команд: {teamCount}/{size}</p>
        <div class="st"><p1>Статус: {status}</p1></div>
    </div>
    
    <div class="block">
        <b>Имя: {name}</b>
        <p>Количество команд: {teamCount}/{size}</p>
        <div class="st"><p1>Статус: {status}</p1></div>
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
        margin-left: 7%;
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
    
    
    </style>