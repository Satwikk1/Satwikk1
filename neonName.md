<!-- fonts -->
<style>
    @import url('https://fonts.googleapis.com/css2?family=Monoton&display=swap');
    @import url('https://fonts.googleapis.com/css2?family=Vibur&display=swap');
</style>

<!-- keyframes -->
<style>
    @keyframes turnonTitle{
        0%, 80%, 83%, 100%{
            text-shadow:
                0 0 7px #fff,
                0 0 10px #fff,
                0 0 21px #fff,
                0 0 42px #f09,
                0 0 82px #f09,
                0 0 92px #f09,
                0 0 102px #f09,
                0 0 151px #f09;
        }
        81%, 82%{
            text-shadow: none;
        }
    }

    @keyframes turnonName{
        0%, 18%, 22%, 25%, 53%, 57%, 100% {
            text-shadow:
            0 0 4px #fff,
            0 0 11px #fff,
            0 0 19px #fff,
            0 0 40px #0fa,
            0 0 80px #0fa,
            0 0 90px #0fa,
            0 0 100px #0fa,
            0 0 150px #0fa;
        }
        
        24%, 55% {        
            text-shadow: none;
        }
    }
</style>

<!-- style readme -->
<style>
    .container{
        margin-bottom: 50%;
    }

    /* ********* name ********** */
    .name{
        display: flex;
        margin: auto;
        width: fit-content;
    }
    .name h1{
        text-align: center;
        font-size: 5em;
        border-bottom: none;
        margin: 0 10px;
        padding: 0px;
        font-family: 'Monoton', cursive;
        color: #fff;
    }
    .name :nth-child(1){
        animation: turnonName 15s linear infinite;
    }
    .name :nth-child(2){
        animation: turnonName 5s linear infinite;
        animation-delay: 3s;
    }

    /* *********** title ************ */
    .title{
        width: fit-content;
        margin: auto;
        margin-left: 64%;
        padding: 0;
    }
    .title p{
        animation: turnonTitle 5s ease-in-out infinite;
        font-size: 3em;
        text-align: center;
        font-family: 'Vibur', cursive;
        color: #fff;
    }


</style>

<!-- readme structure -->
<div class="container">
    <div class="name">
        <h1>Satwik</h1>
        <h1>Singh</h1>
    </div>
    <div class="title">
        <p>web developer</p>
    </div>
</div>

<img width="100%" src="customWave.svg">

<!-- ![](https://komarev.com/ghpvc/?username=Satwikk1&color=blueviolet) -->
