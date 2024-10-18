<script>
  import Header from "$lib/Header.svelte";
</script>

<body>
<Header headingTitle="Contact us" />

<h1>Wanna let us know something?</h1>
<p>
  Here at home page we care. Let us know how you feel about us and we'll think
  about getting back to you
</p>
<br />
<form action="">
  <label for="Name"
    >Name
    <input type="text" name="Name" id="nameBox"/>
  </label>
  <br />
  <label for="email"
    >Email
    <input type="text" name="email" />
  </label>
  <br />
  <br />
  <textarea
    name="message"
    rows="5"
    cols="40"
    placeholder="Type your message here..."
  ></textarea>
  <input type="submit" name="" id="">
</form>
</body>
<style>
#nameBox{
    margin-bottom: 1em;
}
body{
    font-family:Arial, Helvetica, sans-serif;
    background-color:#e2e2e2 ;
}
</style>
