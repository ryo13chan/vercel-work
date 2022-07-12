<template>
  <div class="header">
    <nav>
      <ul class="menu-list">
        <li class="menu">
          <nuxt-link to="/">Home</nuxt-link>
        </li>
        <li class="menu">
          <nuxt-link to="/supplier">Supplier</nuxt-link>
        </li>
        <li class="menu">
          <nuxt-link to="/shop">Shop</nuxt-link>
        </li>
        <li class="menu">
          <nuxt-link to="/user">User</nuxt-link>
        </li>
      </ul>
    </nav>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({
  name: 'AppHeader',
})
</script>

<style lang="scss" scoped>
.header {
  .menu-list {
    display: flex;
    justify-content: end;
    list-style: none;
    gap: 1rem;
    padding: 0 2rem
  }
}
</style>
