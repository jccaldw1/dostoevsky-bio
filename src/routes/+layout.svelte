<script>

    import Navbar from "./Navbar.svelte";

</script>
<div class="app">
    <Navbar/>
    <br/>
    <main>
        This is the main slot.
        <slot/>
        This is the end of the main slot.
    </main>
    <br/>
    <footer>
        This is the footer.
    </footer>
</div>