<script>
export let headingTitle;
</script>

<header>
<nav>
    <ul>
        <li id="title">@Everything <br>Premier League</li>
        <li><a href="/">Home</a></li>
        <li><a href="/game">Play our game</a></li>
        <li><a href="/about">About</a></li>
        <li><a href="/contact">Contact</a></li>
    </ul>
</nav>
</header>

<style>
* {
    box-sizing: border-box; 
    margin: 0; 
    padding: 0; 
}


    nav *{
        background-color: rgb(54, 52, 52);
        padding: 0;
        margin: 0;
    }
    header *{
        font-family: Arial, Helvetica, sans-serif;
        grid-column: 1/span 2;
    }
    #title{
    color: rgb(255, 255, 255);
    text-decoration: none;
    font-size: large;
    font-weight:200;
    padding-top: 1em;
    padding-right: 1em;
    padding-left: 0;
    }
h2{
    display: flex;
    justify-content: center;
    font-weight: 200;
}
li{
    list-style: none;
    border-radius: 1em;
    padding: 0;
    margin: 0;
}
ul{
    display: flex;
    justify-content: space-around;
    border: 0.3em solid rgb(255, 255, 255);
    padding: 0;
    margin: 0;
}
a{
    color: rgb(214, 214, 214);
    text-decoration: none;
    font-size: large;
    font-weight:100;
    display: block;
    padding: 1.5em;
    text-align: center;
    
} 
</style>