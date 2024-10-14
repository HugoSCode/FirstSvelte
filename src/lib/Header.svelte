<script>
export let headingTitle;
</script>

<header>
<h1>{headingTitle}</h1>
<nav>
    <ul>
        <li><a href="/">Home</a></li>
        <li><a href="/">About</a></li>
        <li><a href="/">Contact</a></li>
    </ul>
</nav>
</header>

<style>
    header{
        font-family: sans-serif;
        background-color:lightgray;
        padding: 1em;
    }
h1{
    display: flex;
    justify-content: center;
}
li{
    list-style: none;
    display: flex;
    justify-content: space-between;
    border-radius: 1em;
    border: 2em; border-color:black;
}
ul{
    background-color: darkgray;
    padding:2em;
    display: flex;
    justify-content: space-around;
}
a{
    text-decoration: none;
    font-size: large;
}
</style>