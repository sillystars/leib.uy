<script>
    import { Router, Link, Route } from "svelte-routing";
  
    import Home from "./Home.svelte";
    import About from "./About.svelte";
    import Contact from "./Contact.svelte";
    import Works from "./Works.svelte";
  </script>

<nav class="navbar navbar-expand navbar-light navbar-ghost">
    <div class="d-flex flex-grow-1">
        <Link to="/" class="navbar-brand">Martin Leib</Link>

        <div class="w-100 text-right">
            <button
                class="navbar-toggler"
                type="button"
                data-toggle="collapse"
                data-target="#myNavbar">
                <span class="navbar-toggler-icon" />
            </button>
        </div>
    </div>
    <div class="collapse navbar-collapse flex-grow-1 text-right" id="myNavbar">
        <ul class="navbar-nav ml-auto flex-nowrap">
            <li class="nav-item">
                <Link to="about" class="nav-link m-2 menu-item">About</Link>
            </li>
            <li class="nav-item">
                <a class="nav-link m-2 menu-item verticales">&gt;</a>
            </li>
            <li class="nav-item">
                <Link to="works" class="nav-link m-2 menu-item">Portfolio</Link>
            </li>
            <li class="nav-item">
                <a class="nav-link m-2 menu-item verticales">&gt;</a>
            </li>
            <li class="nav-item">
                <Link to="contact" class="nav-link m-2 menu-item">Contact</Link>
            </li>
        </ul>
    </div>
</nav>

<style>
    * {
        font-family: "Roboto Condensed", sans-serif;
    }
    .navbar-ghost {
        background-color: transparent;
    }
    .navbar-toggler {
        border: none;
        outline: none;
    }
    @media only screen and (max-device-width: 480px) {
        .verticales {
            visibility: hidden;
        }
        .nav-item {
            margin-right: -10px;
            margin-left: -10px;
        }
    }

    @media only screen and (max-width: 600px) {
        .verticales {
            visibility: hidden;
        }
        .nav-item {
            margin-right: -10px;
            margin-left: -10px;
        }
    }

    @media only screen and (max-width: 900px) {
        .verticales {
            visibility: hidden;
        }
        .nav-item {
            margin-right: -10px;
            margin-left: -10px;
        }
    }
</style>
