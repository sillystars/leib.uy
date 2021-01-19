<script>
    import { Router, Link, Route } from "svelte-routing";

    import Home from "./Home.svelte";
    import About from "./About.svelte";
    import Contact from "./Contact.svelte";
    import Works from "./Works.svelte";

    /*
    import {
        Collapse,
        Navbar,
        NavbarToggler,
        NavbarBrand,
        Nav,
        NavItem,
        NavLink,
        UncontrolledDropdown,
        DropdownToggle,
        DropdownMenu,
        DropdownItem,
    } from "sveltestrap";

    let isOpen = false;

    function handleUpdate(event) {
        isOpen = event.detail.isOpen;
    }
    */
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

<!--
<Navbar light expand="md">
    <Link to="/" class="navbar-brand">Martin Leib</Link>
    <NavbarToggler on:click={() => (isOpen = !isOpen)} />
    <Collapse {isOpen} navbar expand="md" on:update={handleUpdate}>
      <Nav class="ml-auto" navbar>
        <NavItem>
            <Link to="about" class="nav-link m-2 menu-item">About</Link>
        </NavItem>
        <NavItem>
            <a class="nav-link m-2 menu-item verticales">&gt;</a>
        </NavItem>
        <NavItem>
            <Link to="works" class="nav-link m-2 menu-item">Portfolio</Link>
        </NavItem>
        <NavItem>
            <a class="nav-link m-2 menu-item verticales">&gt;</a>
        </NavItem>
        <NavItem>
            <Link to="contact" class="nav-link m-2 menu-item">Contact</Link>
        </NavItem>
      </Nav>
    </Collapse>
  </Navbar>
-->
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
            display: none;
            margin-right: -5px;
        }
    }

    @media only screen and (max-width: 600px) {
        .verticales {
            display: none;
            margin-right: -5px;
        }
    }

    @media only screen and (max-width: 900px) {
        .verticales {
            display: none;
        }
    }
</style>
