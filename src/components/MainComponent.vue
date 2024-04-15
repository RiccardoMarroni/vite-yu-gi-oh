<template>
    <main>
        <div class="container">
            <div class="row">
                <div class="col12 col-md-6 col-lg-3">
                    <CardComponent />
                </div>
            </div>
        </div>
    </main>
</template>

<script>
import CardComponent from './CardComponent.vue';
    export default {
        name: 'MainComponent',
        components: {
             CardComponent
        },
        data() {
            return {
            }
        }
    }
</script>

<style lang="scss" scoped>

.container {
    display: flex;
    justify-content: center;
    align-items: center;
    height: calc(100% - 60px);
    background-color: orange;
}

</style>