<script>
    import { scrollto } from 'svelte-scrollto';
</script>

<header id="home" class="text-gray-600 body-font">
    <div
        class="container mx-auto flex flex-wrap p-5 flex-col md:flex-row items-center"
    >
        <a
            href="#"
            class="flex title-font hover:no-underline font-medium items-center mb-4 md:mb-0"
        >
            <i class="fas fa-mug-hot text-yellow-900 dark:text-yellow-600" />
            <span class="ml-3 text-xl text-yellow-900 dark:text-yellow-600"
                >Cafeicultora</span
            >
        </a>
        <nav
            class="md:ml-auto flex flex-wrap items-center text-base justify-center"
        >
            <a
                use:scrollto={'#home'}
                class="mr-5 cursor-pointer text-yellow-900 dark:text-yellow-600 hover:text-yellow-700"
                >Início</a
            >
            <a
                use:scrollto={'#produtos'}
                class="mr-5 cursor-pointer text-yellow-900 dark:text-yellow-600 hover:text-yellow-700"
                >Produtos</a
            >
            <a
                use:scrollto={'#clients'}
                class="mr-5 cursor-pointer text-yellow-900 dark:text-yellow-600 hover:text-yellow-700"
                >Clientes</a
            >
            <a
                use:scrollto={'#contact'}
                class="mr-5 cursor-pointer text-yellow-900 dark:text-yellow-600 hover:text-yellow-700"
                >Contato</a
            >
        </nav>
    </div>
</header>
