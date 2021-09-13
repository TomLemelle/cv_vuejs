<template>
    <section class="languages">
        <TitleSidebar img="language.png" imgDesc="languages" />
        <ul class="languages-list">
            <li>
                <strong>Français</strong>
                <div class="level"></div>
                <p>Langue maternelle</p>
            </li>
            <li>
                <strong>Anglais</strong>
                <div class="level"></div>
                <p>Très bon niveau lu, écrit, parlé.</p>
                <p>17.5/20 au baccalauréat</p>
            </li>
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
.languages {
    margin: 0 45px;

    .languages-list {
        list-style: none;
        font-size: 19px;

        li {
            margin: 30px 0;

            .level {
                margin: 10px 0;
                width: 100%;
                height: 3px;
                background-color: #fff;
            }
        }
    }
}
</style>