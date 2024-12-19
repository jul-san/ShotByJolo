<script>
    import { Navbar, NavBrand, NavLi, NavUl, NavHamburger } from 'flowbite-svelte';
  </script>
  
  <Navbar color="none" class="absolute z-10 flex-col justify-center items-center w-full">
    <div class="w-full flex justify-center">
        <NavBrand href="/" class="flex">
            <img
            src="/logo.png"
            alt="logo"
            class="h-24 w-24 md:h-32 md:w-32 lg:h-50 lg:w-50 xl:h-58 xl:w-58"
        >    
        </NavBrand>
    </div>
  </Navbar>