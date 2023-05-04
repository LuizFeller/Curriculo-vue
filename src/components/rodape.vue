<script>
export default {
    methods: {
        topo () {
            window.scrollTo({top:0, behavior:'smooth'})
        }
    }
}
</script>
<template>

    <div class="volta-topo">
<button @click="topo()">Voltar ao topo</button>

    </div>
</template>