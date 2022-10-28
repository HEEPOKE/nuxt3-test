<template lang="">
  <nav class="navbar navbar-expand-lg bg-light">
    <div class="container-fluid">
      <nuxt-link to="/">
        <a class="navbar-brand">Nuxt</a>
      </nuxt-link>
      <button
        class="navbar-toggler"
        type="button"
        data-bs-toggle="collapse"
        data-bs-target="#navbarText"
        aria-controls="navbarText"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarText">
        <ul class="navbar-nav me-auto mb-2 mb-lg-0">
          <li class="nav-item">
            <nuxt-link to="/">
              <a class="nav-link active" aria-current="page">Home</a>
            </nuxt-link>
          </li>
          <li class="nav-item">
            <nuxt-link to="/store">
              <a class="nav-link">Store</a>
            </nuxt-link>
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>
<script>
export default {
  name: "NavbarVue",
};
</script>
