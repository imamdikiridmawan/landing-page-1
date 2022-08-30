<template>
    <div id="section_nav" class="section_nav">
        <nav class="navbar navbar-expand-lg navbar-light bg-white fixed-top">
        <div class="container">
            <a class="navbar-brand" href="/">
            <img src="@/assets/png/komerce-logo.png" alt="" />
            </a>
            <button
            class="navbar-toggler"
            type="button"
            data-bs-toggle="collapse"
            data-bs-target="#navbarSupportedContent"
            aria-controls="navbarSupportedContent"
            aria-expanded="false"
            aria-label="Toggle navigation"
            >
            <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                <li class="nav-item">
                <a class="nav-link disabled"></a>
                </li>
                <li class="nav-item" id="about">
                <a class="nav-link" aria-current="page" href="/about">About</a>
                </li>
                <li class="nav-item">
                <a class="nav-link disabled"></a>
                </li>
                <li class="nav-item" id="feature">
                <a class="nav-link" aria-current="page" href="/feature">Feature</a>
                </li>
                <li class="nav-item">
                <a class="nav-link disabled"></a>
                </li>
                <li class="nav-item" id="works">
                <a class="nav-link" aria-current="page" href="/works">Works</a>
                </li>
                <li class="nav-item">
                <a class="nav-link disabled"></a>
                </li>
                <li class="nav-item" id="career">
                <a class="nav-link" aria-current="page" href="/career">Career</a>
                </li>
                <li class="nav-item">
                <a class="nav-link disabled"></a>
                </li>
                <li class="nav-item" id="contact">
                <a class="nav-link" aria-current="page" href="/contact">Contact</a>
                </li>
            </ul>
            <form class="d-flex">
                <button class="btn btn-login" type="submit">Login</button>
            </form>
            </div>
        </div>
        </nav>
    </div>
</template>

<script>
export default {

}
</script>

<style src="../assets/css/header.css" />