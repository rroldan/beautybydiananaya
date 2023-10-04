<script lang="ts">
  import { Navbar, NavBrand, NavLi, NavUl, NavHamburger } from 'flowbite-svelte';
</script>

<Navbar rounded color="form">
  <NavBrand href="/">
    <img src="logo.jpg" class="mr-3 h-6 sm:h-9" alt="logo_beauty_by_diananaya" />
    <span class="self-center whitespace-nowrap text-xl font-semibold dark:text-white">Beauty by Diana Anaya</span>
  </NavBrand>
  <NavHamburger />
  <NavUl>
    <NavLi href="/" active={true}>Home</NavLi>
    <NavLi href="/contact">Contacto</NavLi>
  </NavUl>
</Navbar>