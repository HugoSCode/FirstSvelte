<script>
export let headingTitle;
</script>

<header>
<h1>{headingTitle}</h1>
<nav>
    <ul>
        <li><a href="/">Home</a></li>
        <li><a href="/about">About</a></li>
        <li><a href="/contact">Contact</a></li>
    </ul>
</nav>
</header>

<style>
    header{
        font-family: sans-serif;
        background-color:lightgray;
        padding-left: 0;
        padding-right: 0;
    }
h1{
    display: flex;
    justify-content: center;
}
li{
    list-style: none;
    border-radius: 1em;
}
ul{
    background-color: rgb(103, 134, 238);
    display: flex;
    justify-content: space-around;
    border: 1em solid black;
    
}
a{
    color: black;
    text-decoration: none;
    font-size: large;
    font-weight: bold;
    display: block;
    padding: 1.5em;
    text-align: center;
}
</style>