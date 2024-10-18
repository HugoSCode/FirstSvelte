<script>
import Header from "$lib/Header.svelte";
</script>


<body>

    <Header headingTitle="Our new game"></Header>

    <section class="column1">

        <h3>Our mission</h3>
        <p>Using state of the art simulation technology we've created the ultimate football match simulator with uncanny accuracy</p>
    </section>



</body>

<style>
body{
display: grid;
grid-template-columns: 1fr 1fr	;
}
.column1 {
    grid-column: 1;
}
Header{
}
</style>