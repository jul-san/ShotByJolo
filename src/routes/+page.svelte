<script>
  import { Video } from 'flowbite-svelte';
  import Header from "$lib/components/Header.svelte";
  import Videocard from "$lib/components/Videocard.svelte";
  import Footer from '$lib/components/Footer.svelte';
</script>


<Header/>
<Video src="/highlights.mp4" autoplay muted loop disablePictureInPicture class="pointer-events-none absolute z-0 w-full h-full object-cover"/>
<Footer/>
