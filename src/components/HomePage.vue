<template>
    <div class="home">
        <section class="hero is-primary">
            <div class="hero-body has-text-centered">
                <div class="container">
                    <img src="../assets/logo.png">
                    <h1 class="title">Welcome to NodeMC</h1>
                </div>
            </div>
        </section>
        <footer class="footer">
            <div class="columns">
                <div class="column is-quarter is-offset-one-quarter">
                    <h2 class="is-size-4-desktop is-size-5">About</h2>
                    <strong>NodeMC Dashboard</strong> by the <a href="https://github.com/NodeMC">NodeMC Team</a>.
                </div>
                <div class="column is-quarter">
                    <h2 class="is-size-4-desktop is-size-5">Built with</h2>
                    <ul>
                        <li><a href="http://router.vuejs.org/" target="_blank">vue-router</a></li>
                        <li><a href="http://vuex.vuejs.org/" target="_blank">Vuex</a></li>
                        <li><a href="https://bulma.io/" target="_blank">Bulma</a></li>
                        <li><a href="https://buefy.github.io/" target="_blank">Buefy</a></li>
                    </ul>
                </div>
            </div>
        </footer>
    </div>
</template>

<script>
export default {
    name: "home",
};
</script>

<style lang="scss" scoped>
.hero-body .container img {
    width: 256px;
    height: 256px;
}
</style>

