<div class="abinf vc hc" style="font-size: 125%">
    <p id="title">
        <span
            class="animate__animated animate__fadeInUp"
            style="webkit-animation-delay: 0.5s; animation-delay: 0.5s;"
            >Whats up?</span
        > <br /><br />
        <span
            class="animate__animated animate__fadeInUp"
            style="webkit-animation-delay: 1.0s; animation-delay: 1.0s;"
            >I'm Martin - and as I said on the home page - I'm a 15 year old web
            developer and artist from Uruguay.</span
        > <br /><br />
        <span
            class="animate__animated animate__fadeInUp"
            style="webkit-animation-delay: 1.5s; animation-delay: 1.5s;"
            >I'm a self-motivated person and I've taught myself everything I
            know about coding today.</span
        > <br /><br />
        <span
            class="animate__animated animate__fadeInUp"
            style="webkit-animation-delay: 2.0s; animation-delay: 2.0s;"
            >I can speak fluently three languages: Spanish (which is my main
            language), English and Portuguese, so, if you have a project, or
            want to work with me, feel free to <a href="/contact">contact me</a> in any of these three
            languages! 🙂</span
        >
    </p>
</div>

<style>
    * {
        font-family: "Roboto Condensed", sans-serif;
    }

    .abinf {
        width: 75%;
    }

    .bg-dark {
        background-color: #0d0f11 !important;
    }

    #title {
        text-align: center;
    }

    a {
        text-decoration: none !important;
        color: #7700ff !important;
        opacity: 100% !important;
        transition: 0.3s !important;
    }

    a:hover {
        color: #7700ff !important;
        text-decoration: none !important;
        opacity: 90% !important;
    }

    .main0 {
        height: 100vh;
        width: 100vw;
    }

    .vc {
        position: absolute;
        top: 50%;
        left: 50%;
        transform: translate(-50%, -50%);
        width: 50%;
    }

    .hc {
        width: 50%;
        margin: 0 auto;
        text-align: center;
    }

    .align-items-center {
        -ms-flex-align: center !important;
        align-items: center !important;
    }

    .d-flex {
        display: -ms-flexbox !important;
        display: flex !important;
    }

    #custom-underline {
        position: relative;
        text-decoration: none;
        padding-bottom: 8px;
    }

    #custom-underline:before,
    #custom-underline:after {
        content: "";
        position: absolute;
        bottom: 2px;
        left: 0;
        right: 0;
        height: 2px;
        background-color: #7700ff;
    }

    #custom-underline:before {
        opacity: 0;
        -webkit-transform: translateY(-8px);
        transform: translateY(-8px);
        -webkit-transition: opacity 0s,
            -webkit-transform 0s cubic-bezier(0.175, 0.885, 0.32, 1.275);
        transition: opacity 0s,
            -webkit-transform 0s cubic-bezier(0.175, 0.885, 0.32, 1.275);
        transition: transform 0s cubic-bezier(0.175, 0.885, 0.32, 1.275),
            opacity 0s;
        transition: transform 0s cubic-bezier(0.175, 0.885, 0.32, 1.275),
            opacity 0s,
            -webkit-transform 0s cubic-bezier(0.175, 0.885, 0.32, 1.275);
    }

    #custom-underline:after {
        opacity: 0;
        -webkit-transform: translateY(4px);
        transform: translateY(4px);
        -webkit-transition: opacity 0.2s,
            -webkit-transform 0.2s cubic-bezier(0.175, 0.885, 0.32, 1.275);
        transition: opacity 0.2s,
            -webkit-transform 0.2s cubic-bezier(0.175, 0.885, 0.32, 1.275);
        transition: transform 0.2s cubic-bezier(0.175, 0.885, 0.32, 1.275),
            opacity 0.2s;
        transition: transform 0.2s cubic-bezier(0.175, 0.885, 0.32, 1.275),
            opacity 0.2s,
            -webkit-transform 0.2s cubic-bezier(0.175, 0.885, 0.32, 1.275);
    }

    #custom-underline:hover:before,
    #custom-underline:hover:after,
    #custom-underline:focus:before,
    #custom-underline:focus:after {
        opacity: 1;
        -webkit-transform: translateY(0);
        transform: translateY(0);
    }

    #custom-underline:hover:before,
    #custom-underline:focus:before {
        -webkit-transition: opacity 0.2s,
            -webkit-transform 0.2s cubic-bezier(0.175, 0.885, 0.32, 1.275);
        transition: opacity 0.2s,
            -webkit-transform 0.2s cubic-bezier(0.175, 0.885, 0.32, 1.275);
        transition: transform 0.2s cubic-bezier(0.175, 0.885, 0.32, 1.275),
            opacity 0.2s;
        transition: transform 0.2s cubic-bezier(0.175, 0.885, 0.32, 1.275),
            opacity 0.2s,
            -webkit-transform 0.2s cubic-bezier(0.175, 0.885, 0.32, 1.275);
    }

    #custom-underline:hover:after,
    #custom-underline:focus:after {
        -webkit-transition: opacity 0s 0.2s,
            -webkit-transform 0s 0.2s cubic-bezier(0.175, 0.885, 0.32, 1.275);
        transition: opacity 0s 0.2s,
            -webkit-transform 0s 0.2s cubic-bezier(0.175, 0.885, 0.32, 1.275);
        transition: transform 0s 0.2s cubic-bezier(0.175, 0.885, 0.32, 1.275),
            opacity 0s 0.2s;
        transition: transform 0s 0.2s cubic-bezier(0.175, 0.885, 0.32, 1.275),
            opacity 0s 0.2s,
            -webkit-transform 0s 0.2s cubic-bezier(0.175, 0.885, 0.32, 1.275);
    }

    a {
        text-decoration: none;
        position: relative;
        transition: all 0.6s;
        color: #7700ff;
    }

    a:hover {
        text-decoration: none;
        color: #7700ff;
    }

    a:before {
        content: "";
        width: 0;
        height: 0.1em;
        position: absolute;
        bottom: 0;
        right: 0;
        background: #7700ff;
        transition: all 0.3s;
    }

    a:hover:before {
        width: 100%;
        left: 0;
        background: #7700ff;
    }
</style>
