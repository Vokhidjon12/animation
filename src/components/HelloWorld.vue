<template>
  <div>
        <div class="loader">
        <span>M</span>
        <span>A</span>
        <span>R</span>
        <span>J</span>
        <span>O</span>
        <span>N</span>
        <span>A</span>
        <span><img src="@/assets/heart.png" alt="img"></span>
    </div>
  </div>
</template>

<style scoped>
*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
.loader{
  position: absolute;
  top: 50%;
  left: 50%;
}
body{
    font-family: sans-serif;
    min-height: 100vh;
    display: flex;
    align-items: center;
    justify-content: center;
    background-color: #111;
}
.loader span {
    font-size: 60px;
    text-transform: uppercase;
    color: aqua;
    font-weight: bold;
    animation: animate 5s ease-in-out infinite;
}
.loader span img {
    max-width: 50px;
}

@keyframes animate{
    10%{color: yellow ;}
    20%{color: green ;}
    30%{color: pink ;}
    40%{color: blue ;}
    50%{color: orange ;}
    60%{color: darkred ;}
    70%{color: darkblue ;}
    80%{color: yellowgreen ;}
    90%{color: orangered ;}
    100%{color: aqua ;}
}


.loader span:nth-child(1){
    animation-delay: 0.8s;
}
.loader span:nth-child(2){
    animation-delay: 1s;
}
.loader span:nth-child(3){
    animation-delay: 1.2s;
}
.loader span:nth-child(4){
    animation-delay: 1.4s;
}
.loader span:nth-child(5){
    animation-delay: 1.6s;
}
.loader span:nth-child(6){
    animation-delay: 1.8s;
}
.loader span:nth-child(7){
    animation-delay: 2s;
}
.loader span:nth-child(8){
    animation-delay: 2.2s;
}
.loader span:nth-child(9){
    animation-delay: 2.4s;
}
.loader span:nth-child(10){
    animation-delay: 2.6s;
}
</style>