<script>
import AppCardsOrder from "./AppCardsOrder.vue"

export default {
    name: "AppMain",
    components: {
        AppCardsOrder
    }
}
</script>

<template>
    <div class="wrapper-main">
        <div class="wrapper-container ">
            <section class="container">
                <select name="" id="">
                    <option value="">prova1</option>
                    <option value="">prova2</option>
                    <option value="">prova3</option>
                </select>
                <AppCardsOrder />
            </section>
        </div>
    </div>
</template>

<style scoped lang="scss">
    @use "../styles/partials/variables" as *;
    .wrapper-main {
        width: 100%;
        background-color: $maincolor;
        section {
            padding: 40px 0 0 0;
            select {
                width: 180px;
            }
        }
    }
</style>