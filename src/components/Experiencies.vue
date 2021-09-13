<template>
  <section class="experiencies">
    <Card
        date="De novembre 2020 à juillet 2021"
        name="Développeur web Front / Back"
        company="Keyveo, &nbsp;"
        address="Le Petit-Quevilly, France"
        desc="Réalisation d'un outil permettant la visualisation d'environnement en 3D."
        stack="Stack: Three.js / Aframe / Angular / NodeJS / ExpressJS / Microsoft SQL / Azure"
    />
    <Card
        date="De mai 2020 à août 2020"
        name="Développeur web Front / Back"
        company="Maisons France Style, &nbsp;"
        address="Boos, France"
        desc="Développement et optimisation du site web de l'entreprise."
        stack="Stack: Html / Scss / JavaScript / Php"
    />
    <Card
        date="Septembre 2019"
        name="Stagiaire polyvalent"
        company="ADL Services, &nbsp;"
        address="Franqueville-Saint-Pierre, France"
        desc="Installation et configuration de réseaux informatiques."
    />
    <Card
        date="De février 2017 à avril 2017"
        name="Stagiaire polyvalent"
        company="L'informatique, &nbsp;"
        address="Rouen, France"
        desc="Dépannage informatique et réseau, conseil et vente de matériel, assemblage d'ordinateurs, installation et configuration de parcs informatiques."
    />
    <Card
        date="De juin 2016 à juillet 2016"
        name="Stagiaire polyvalent"
        company="Andchor, &nbsp;"
        address="Rouen, France"
        desc="Développement de sites internet, mise en place de stratégies marketing, rendez-vous client."
    />
  </section>
</template>

<script>

import Card from "./Card";

export default {
    components: {
        Card,
    }
}
</script>

<style>

.experiencies {
    margin-bottom: 60px;
}

</style>