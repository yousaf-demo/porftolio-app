<template>
<section class="main-navbar">
    <div class="container">
        <div class="navbar-wrapper">

            <ul class="d-flex justify-content-between list-unstyled">
                <li>
                    <div class="logo-wrapper">
                        <img src="../assets/logo.png" alt="">
                    </div>
                </li>
                <li>
                    <ul class="d-flex gap-4 list-unstyled">
                        <li>
                            <a href="#">Home</a>
                        </li>
                        <li>
                            <a href="#">Work</a>
                        </li>
                        <li>
                            <a href="#">Contact</a>
                        </li>
                    </ul>
                </li>
            </ul>

        </div>
    </div>

</section>
</template>
<script>
export default {
    name: 'MainNavbar'
}
</script>
<style>
.navbar-wrapper .logo-wrapper{
    width: 50px;
    height: 50px;
}
</style>