<template>
    <nav class="navbar navbar-expand-lg navbar-dark sticky-top">
        <div class="container-fluid">
            <router-link to="/" class="navbar-brand fw-bold">
                🌤 El Tiempo
            </router-link>

            <button
                class="navbar-toggler"
                type="button"
                data-bs-toggle="collapse"
                data-bs-target="#menuNav"
                aria-controls="menuNav"
                aria-expanded="false"
                aria-label="Toggle navigation"
            >
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="menuNav">
                <div class="navbar-nav ms-auto align-items-center">
                    <router-link to="/" class="nav-link"> Home </router-link>

                    <router-link to="/about" class="nav-link">
                        Nosotros
                    </router-link>
                </div>
            </div>
        </div>
    </nav>
</template>

<style scoped>
.navbar {
    background-color: #071629;
    color: #ffffff;
    padding: 1rem 0;
}
</style>
