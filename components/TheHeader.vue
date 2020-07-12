<template>
  <header class="flex">
    <nav class="main-nav">
        <ul class="nav-links">
            <NuxtLink to="/" tag="li"><a>All Posts</a></NuxtLink>
            <NuxtLink to="/about" tag="li"><a>About</a></NuxtLink>
        </ul>
    </nav>
    <NuxtLink to="/"><Logo class="mb-4" /></NuxtLink>
    <AppSearchInput class="ml-8" />
  </header>
</template>

<style scoped>
.main-header {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    background: #022d30;
    height: 4.5rem;
}

.main-nav {
    height: 100%
}

.nav-links {
    list-style: none;
    margin: 0;
    padding: 0;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100%;
}

.nav-link {
    height: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
    margin: 0 rem;
    padding: 0.3rem;
}

.nav-link a {
    display: block;
    text-decoration: none;

}
</style>