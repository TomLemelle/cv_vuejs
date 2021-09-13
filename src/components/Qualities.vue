<template>
    <section class="qualities">
        <TitleSidebar img="trophy.png" imgDesc="qualités" quality="Qualités" />
        <ul class="quality-list">
            <li>Polyvalent</li>
            <li>Motivé</li>
            <li>Autodidacte</li>
            <li>Créatif</li>
        </ul>
    </section>
</template>

<script>
import TitleSidebar from "./TitleSidebar.vue";

export default {
    components: {
        TitleSidebar,
    }
}
</script>

<style lang="scss">
.qualities {
    margin: 0 45px;

    .quality-list {
        list-style: none;
        font-size: 18px;
        font-weight: bold;

        li {
            margin: 30px 0;
        }

        li:first-of-type {
            margin-top: -15px;
        }
    }
}
</style>