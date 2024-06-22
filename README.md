# pricing-landing-page
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pricing page</title>
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css" integrity="sha512-SnH5WK+bZxgPHs44uWIX+LLJAJ9/2PkPKZ5QiAj6Ta86w+fsb2TkcmfRyVX3pBnMFcV7oQPJkl9QevSCWr3W6A==" crossorigin="anonymous" referrerpolicy="no-referrer" />
    
</head>
<body>

    <div class="wrapper">
        <div class="card">
            
                <h3><u>Best</u></h3>
             <h1>$20 <span>/Month</span></h1>
            
             <hr>
             <p>For Most Business that want to optimise their web queries.</p>
             <hr> 
             <ul>
                <ul>
                 <li><input type="checkbox" name="" id=""> All Limited Links </li>
                 <li><input type="checkbox" name="" id=""> Own Analytics platform </li>
                 <li><input type="checkbox" name="" id=""> Chat Support</li>
                 <li><input type="checkbox" name="" id=""> Optimise Hashtags </li>
                 <li><input type="checkbox" name="" id=""> Unlimited Users</li>
                 <li><input type="checkbox" name="" id="">limited users </li>
                </ul>
             </ul>
             <a href="#">choose plan</a>
            

        </div> 

        <div class="card">
            <h3><u>Normal</u></h3>
            <h1>$15 <span>/Month</span></h1>
            <hr>
            <p>For Most Business that want to optimise their web queries.</p>
            <hr> 
            <ul>
                <li><input type="checkbox" name="" id=""> All Limited Links </li>
                <li><input type="checkbox" name="" id=""> Own Analytics platform </li>
                <li><input type="checkbox" name="" id=""> Chat Support</li>
                <li><input type="checkbox" name="" id=""> Optimise Hashtags </li>
                <li><input type="checkbox" name="" id="">Unlimited users </li>
            </ul>
            <a href="#">choose plan</a>

        </div>

        <div class="card active">
            <h3><u>Premium</u></h3>
            <h1>$30 <span>/Month</span></h1>
            <hr>
            <p>For Most Business that want to optimise their web queries.</p>
            <hr> 
            <ul>
                <li><input type="checkbox" name="" id=""> All Limited Links </li>
                <li><input type="checkbox" name="" id=""> Own Analytics platform </li>
                <li><input type="checkbox" name="" id=""> Chat Support </li>
                <li><input type="checkbox" name="" id=""> Optimise Hashtags </li>
                <li><input type="checkbox" name="" id=""> Unlimited Users</li>
                <li><input type="checkbox" name="" id=""> limited users </li>
                 
                
            </ul>
            <a href="#">choose plan</a>

        </div>
        
        <div class="card">
            <h3><u>Normal</u></h3>
            <h1>$15 <span>/Month</span></h1>
            <hr>
            <p>For Most Business that want to optimise their web queries.</p>
            <hr> 
            <ul>
                <li><input type="checkbox" name="" id=""> All Limited Links </li>
                <li><input type="checkbox" name="" id=""> Own Analytics platform </li>
                <li><input type="checkbox" name="" id=""> Chat Support</li>
                <li><input type="checkbox" name="" id=""> Optimise Hashtags </li>
                <li><input type="checkbox" name="" id="">Unlimited users </li>
            </ul>
            <a href="#">choose plan</a>

        </div>

        <div class="card">
            <h3><u>Base</u></h3>
            <h1>$10 <span>/Month</span></h1>
            <hr>
            <p>For Most Business that want to optimise their web queries.</p>
            <hr> 
            <ul>
                <li><input type="checkbox" name="" id=""> All Limited Links </li>
                <li><input type="checkbox" name="" id=""> Own Analytics platform </li>
                <li><input type="checkbox" name="" id=""> Chat Support</li>
                <li><input type="checkbox" name="" id="">Unlimited users </li>
            </ul>
            <a href="#">choose plan</a>

        </div>

    </div>
    
</body>
</html>
#css.


*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: sans-serif;
}

body{
    justify-content: center;
    align-items: center;
    display: flex; 
    width: 100%;
    background: linear-gradient(to top, rgba(0,0,0,0.5)50%,rgba(0,0,0,0.5)50%) ;
    background-position: center;
    background-size: cover;
    height: 109vh;
}

.wrapper{
    display: flex;
    justify-content: center;
    align-items: center;
    color: rgba(0,0,0,0.7);
}


.wrapper .card {
    max-width: 300px;
    background-color: #daa520;
    padding: 40px;
    margin: 30px 15px;
    border-radius: 10px;
    box-shadow: 10px 10px 10px -1px rgba(10,99,169,0,16),
    3px 3px 10px -1px rgba(255, 255, 255, 0.7);
}
/* For Active Class*/
.wrapper .card.active{
    background-color: #5f38e2;
    transform: scale(1, 1.09);
}


.wrapper .card h3{
    margin-bottom: 15px;
}

/* For Active Class*/
.wrapper .card.active h3{
    color: rgba(255,255,255,1);
    transform: scale(1, 1.09);
}

.wrapper .card h1{
    margin-bottom: 10px;
    color: rgba(0,0,0,1);
    font-size: 2.5rem;
}

/* For Active Class*/
.wrapper .card.active h1{
    color: rgba(255,255,255,1);
}

.wrapper .card h1 span{
    font-size: 12px;
    color: rgba(0,0,0,0.7);
}

/* For Active Class*/
.wrapper .card.active h1 span{
    color: rgba(255,255,255,0.9);
    
}

.wrapper .card p{
    margin: 20px 0;
    color: rgba(0,0,0,0.6);
    font-size: 14px;
    line-height: 1.5;
}

/* For Active Class*/
.wrapper .card.active p{
    color: rgba(255,255,255,1);
    
}

.wrapper .card ul{
    list-style: none;
}

.wrapper .card ul li{
    line-height: 3;
    color: rgba(0,0,0,0.9);
}

/* For Active Class*/
.wrapper .card.active li{
    color: rgba(255,255,255,0.9);
    
}

.wrapper .card ul li input{
    margin-right: 10px;
    color: rgba(0,0,0,0.4);
}

/* For Active Class*/
.wrapper .card.active li input{
    color: rgba(255,255,255,0.9);
    
}

.wrapper .card a{
    margin: 20px 0;
    text-align: center;
    display: block;
    text-decoration: none;
    border: 1px solid #111;
    color: white;
    padding: 15px;
    font-weight: bold;
    transition: 0.4s;
    border-radius: 5px;
}

/* For Active Class*/
.wrapper .card.active a{
    background-color: white;
    color: rgba(0,0,0,1);
    
}

.wrapper .card a:hover{
    background-color: #5f38e2;
    color: white);
}

/* For Active Class*/
.wrapper .card.active a:hover{
    border: 1px solid white;
    
}
