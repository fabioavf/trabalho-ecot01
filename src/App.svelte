<script>
    import Tailwindcss from './Tailwindcss.svelte';
    import '../node_modules/@fortawesome/fontawesome-free/js/all';
    import Header from './components/Header.svelte';
    import Hero from './components/Hero.svelte';
    import Produtos from './components/Produtos.svelte';
    import Clients from './components/Clients.svelte';
    import Contact from './components/Contact.svelte';
    import Footer from './components/Footer.svelte';
</script>

<Tailwindcss />

<Header />
<Hero />
<Produtos />
<Clients />
<Contact />
<Footer />

<style>
    :global(body) {
        padding: 0;
    }

    @media (prefers-color-scheme: dark) {
        :global(body) {
            @apply bg-gray-900;
        }
    }
</style>
