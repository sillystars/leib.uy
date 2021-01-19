<script>
    import Navbar from "./Navbar.svelte";
    import Info from "./Info.svelte";
    import Footer from "./Footer.svelte";
</script>

<svelte:head>
    <title>Martin G. Leib</title>
    <link
        rel="stylesheet"
        href="https://cdn.jsdelivr.net/npm/bootstrap@4.5.3/dist/css/bootstrap.min.css"
        integrity="sha384-TX8t27EcRE3e/ihU7zmQxVncDAy5uIKz4rEkgIXeMed4M0jlfIDPvg6uqKI2xXr2"
        crossorigin="anonymous"
    />

    <link
        rel="stylesheet"
        href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css"
    />

    <link
        rel="stylesheet"
        href="https://pagecdn.io/lib/hover/2.3.1/css/hover-min.css"
    />

    <link rel="preconnect" href="https://fonts.gstatic.com" />
    <link
        href="https://fonts.googleapis.com/css2?family=Roboto+Condensed&display=swap"
        rel="stylesheet"
    />
</svelte:head>

<Navbar />
<Info />
<Footer />
