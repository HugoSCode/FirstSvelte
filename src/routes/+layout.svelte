<script>
    import Navigation from "$lib/Navigation.svelte"
    import Header from "$lib/Header.svelte";
</script>
<Navigation />
<Header />

<slot />

<footer>
   <p>@My footer</p> 

</footer>

<style>
   :global(*) {
        font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
    }
  

    footer{
        color: white;
        padding: 1.5em;
        background-color: rgb(46, 46, 46);
        margin-top: 1em;
        border-top: 0.15em solid red;
        position: fixed;
        bottom: 0;
        width:100%
    }
    footer p{
        font-weight: 200;
    }
</style>