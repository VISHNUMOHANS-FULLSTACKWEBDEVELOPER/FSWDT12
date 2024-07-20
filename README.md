# FSWDT12
DAY 12
<!DOCTYPE html>
<html>
    <head>
        <title>Animations and media query</title>
        <link rel="stylesheet" href="./day12.css"/>
    </head>
    <body>
        <div>hello guys</div>
        <div class="box">
            <div class="ball"></div>
            <!-- Media queries is used for accomplshing syles for various devices and for building responsive website,or updae or add styles at particular trigger points(screen size)  -->
        </div>
    </body>
</html>
.box{
    background-color: black;
    height: 100vh;
    width: 100vw;
}
.ball{
    background-color: yellow;
    border-radius: 100px;
    height: 100px;
    width: 100px;
}
.ball:hover{
    animation: movetheball 5s ease-in-out forwards;
}
@keyframes movetheball{
     25%{   
        transform:translate(1000%);
     }
     50%{
        transform:translate(800%,200%);
        background-color: blueviolet;
        border-radius: 12%;
     }
     75%{   
        transform:translate( 0,1000%);
        background-color: green;
        border-radius: 20%;
     } 
     100%{   
        transform:translate(0 0);
     }
}
