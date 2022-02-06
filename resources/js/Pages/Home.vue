<template>
    <figure
        class="md:flex bg-slate-100 rounded-xl p-8 md:p-0 dark:bg-slate-800 w-3/4 md:w-1/2 mx-auto mt-8 md:mt-10"
    >
        <img
            class="w-24 h-24 md:w-48 md:h-auto md:rounded-none rounded-full mx-auto"
            src="img/sarah-dayan.jpg"
            alt=""
            width="384"
            height="512"
        />
        <div class="pt-6 md:p-8 text-center md:text-left space-y-4">
            <blockquote>
                <p class="text-lg font-medium">
                    “Se você quer ser bem-sucedido precisa de dedicação total,
                    buscar seu último limite e dar o melhor de si mesmo”
                </p>
            </blockquote>
            <figcaption class="font-medium">
                <!-- text right -->

                <div class="text-sky-500 dark:text-sky-400 text-right">
                    Ayrton Senna
                </div>
            </figcaption>
        </div>
    </figure>
</template>

<script>
export default {
    props: {
        title: String,
    },
};
</script>

<style></style>
