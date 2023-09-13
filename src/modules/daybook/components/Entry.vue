<template>
    <div class="entry-container mb-3 pointer p-2" @click="$router.push({ name: 'entry', params: { id: 10 } })">

        <!-- Titulo -->
        <div class="entry-title d-flex">
            <span class="text-success fs-5 fw-bold">12</span>
            <span class="mx-1 fs-5">Septiembre</span>
            <span class="mx-2 fw-light">2023, martes</span>
        </div>

        <div class="entry-description">
            Ullamco culpa voluptate est ex cupidatat culpa elit labore quis elit tempor. Laborum nulla qui qui duis eiusmod
            ullamco cillum est ipsum eiusmod aliqua ut. Ullamco et eu anim tempor eu nisi sunt culpa sit duis esse
            consectetur ipsum. Aute esse anim occaecat ex laborum adipisicing reprehenderit consequat deserunt. Proident
            ullamco pariatur non nostrud cupidatat irure officia culpa aliquip quis et fugiat. Fugiat est ullamco laboris
            aliqua Lorem Lorem veniam exercitation est dolore incididunt.
        </div>
    </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
.entry-container {
    border-bottom: 1px solid #2c3e50;
    transition: 0.2s all ease-in;

    &:hover {
        background-color: lighten($color: grey, $amount: 45);
    }

    .entry-description {
        font-size: 12px;
    }
}
</style>