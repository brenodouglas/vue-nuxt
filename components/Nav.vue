<template>
    <nav class="nav">
        <div class="nav-left">
            <a class="nav-item">
            <img src="http://bulma.io/images/bulma-logo.png" alt="Bulma logo">
            </a>
        </div>

        <div class="nav-center">
           
        </div>

        <!-- This "nav-toggle" hamburger menu is only visible on mobile -->
        <!-- You need JavaScript to toggle the "is-active" class on "nav-menu" -->
        <span class="nav-toggle">
            <span></span>
            <span></span>
            <span></span>
        </span>

        <!-- This "nav-menu" is hidden on mobile -->
        <!-- Add the modifier "is-active" to display it on mobile -->
        <div class="nav-right nav-menu">
             <a class="nav-item is-tab " href="#">
                Home
            </a>
            <a class="nav-item is-tab " href="#">
                Sobre
            </a>
            <a class="nav-item is-tab " href="#">
                Serviços
            </a>
            <a class="nav-item is-tab is-active" href="#">
                Blog
            </a>
            <a class="nav-item is-tab " href="#">
                Contato
            </a>
            <div class="nav-item">
                <div class="field is-grouped">
                    <p class="control">
                        <a class="button" >
                            <span class="icon">
                            <i class="fa fa-twitter"></i>
                            </span>
                            <span>Twitter</span>
                        </a>
                    </p>
                    <p class="control">
                        <a class="button">
                            <span class="icon">
                            <i class="fa fa-facebook"></i>
                            </span>
                            <span>Facebook</span>
                        </a>
                    </p>
                </div>
            </div>
        </div>
    </nav>
</template>
