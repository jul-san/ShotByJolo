<script>
    import { Card } from 'flowbite-svelte';

    const card_info = [
        {image: "/sexy_red.jpg"},
        {image: "/elvy_the_god.jpg"},
        {image: "/fredo_bang.jpg"},
        {image: "/twelve_honcho.jpg"},
        {image: "/lil_snipe.jpg"},
        {image: "/rod_wave.jpg"},
        {image: "/roddy_rackzz.jpg"},
        {image: "/dj_chose.jpg"},
        {image: "/ynw_bslime.jpg"},
        {image: "/yung_cali.jpg"},
        {image: "/lil_snipe.jpg"},
        {image: "/snot.jpg"},
        {image: "/vicktuff.jpg"},
    ];
</script>

<div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-1 p-1">
    {#each card_info as card}
    <Card padding="none" href="/cards" class="w-full transition-transform duration-700 hover:-translate-y-1 hover:shadow-xl">
        <img src={card.image} alt="julian">
    </Card>
    {/each}
</div>
