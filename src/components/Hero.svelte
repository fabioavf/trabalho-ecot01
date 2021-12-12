<script>
    import { scrollto } from 'svelte-scrollto';
</script>

<section class="text-gray-600 dark:text-gray-400 body-font">
    <div
        class="container mx-auto flex px-5 py-24 md:flex-row flex-col items-center"
    >
        <div
            class="lg:flex-grow md:w-1/2 lg:pr-24 md:pr-16 flex flex-col md:items-start md:text-left mb-16 md:mb-0 items-center text-center"
        >
            <h1
                class="title-font sm:text-4xl text-3xl mb-4 font-medium text-gray-900 dark:text-gray-100"
            >
                Conheça nossos cafés
            </h1>
            <p class="mb-8 leading-relaxed">
                Lorem ipsum dolor sit amet consectetur, adipisicing elit. Minus,
                quibusdam harum aperiam excepturi eaque nostrum nisi placeat
                ipsum! Eum facere harum minus, sapiente a nesciunt quae
                consectetur voluptatibus necessitatibus impedit!
            </p>
            <div class="flex justify-center">
                <button
                    use:scrollto={'#contact'}
                    class="inline-flex text-white bg-yellow-900 dark:bg-yellow-600 border-0 py-2 px-6 focus:outline-none hover:bg-yellow-700 rounded text-lg"
                    >Entre em contato</button
                >
            </div>
        </div>
        <div class="lg:max-w-lg lg:w-full md:w-1/2 w-5/6">
            <img
                class="object-cover object-center rounded"
                alt="hero"
                src="https://dummyimage.com/720x600"
            />
        </div>
    </div>
</section>
