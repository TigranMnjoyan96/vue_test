<template>
    <nav>
        <div class="nav-wrapper">
            <router-link to="/" class="brand-logo">Logo</router-link>
            <ul id="nav-mobile" class="right hide-on-med-and-down">
                <router-link tag="li"
                             to="/"
                             exact active-class="active"
                ><a>Sass</a></router-link>
                <router-link tag="li"
                             to="/smth"
                              active-class="active"
                ><a>sdvk</a></router-link>
            </ul>
        </div>
    </nav>
</template>

<script>
    export default {
        name: "Navbar"
    }
</script>

<style scoped>

</style>