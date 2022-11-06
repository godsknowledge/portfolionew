<template>
    <article class="intro-text">
        <p class="intro-hello">My name is Mahatir Said.</p>
        <h1>I'm a SharePoint Consultant<br>& FullStack Developer.</h1>
        <p class="content">Currently, I work at Camdere Consulting.</p>
    <SocialNetworks />
    </article>

</template>

<script>

import SocialNetworks from '@/components/SocialNetworks.vue';

export default {
    components: {
        SocialNetworks
    }
}

</script>

<style lang="scss" scoped>
.intro-text {
    color: $ciWhite;
    max-width: 40rem;
    font-family: $roboto;
    p {
        font-size: 1.5rem;
        padding: 0;
        margin: 0;
        &.intro-hello {
            margin: 2rem 0 1rem 0;
        }
        &.content {
            margin: 0 0 2rem 0;
            line-height: 1.4em;
            color: $ciGrey;
        }
    }
    h1 {
        font-size: 2.5rem;
        padding: 0;
        margin: 0 0 1rem 0;
    }
}
</style>