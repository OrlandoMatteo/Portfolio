<script setup>
// Import AgnosticUI global common & component CSS
import "agnostic-vue/dist/common.min.css";
import "agnostic-vue/dist/index.css";
import { Header, HeaderNav, HeaderNavItem } from "agnostic-vue";
</script>
<template>
  <h3 class="mbe12">Header defaults to space between</h3>
  <Header>
    <template v-slot:logoleft>
      <a href="https://web.dev/">web.dev</a>
    </template>
    <template v-slot:headernav>
      <HeaderNav>
        <HeaderNavItem>
          <a href="https://css-tricks.com/">CSS-Tricks</a>
        </HeaderNavItem>
        <HeaderNavItem>
          <a href="https://developer.mozilla.org/en-US/">MDN</a>
        </HeaderNavItem>
      </HeaderNav>
    </template>
    <template v-slot:logoright>
      <a href="https://www.freecodecamp.org/">freeCodeCamp</a>
    </template>
  </Header>
</template>