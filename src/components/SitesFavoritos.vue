<template>
    <div class="sites-favoritos">
        <h2>Sites Favoritos</h2>
        <ul>
            <li v-for="site of sitesFavoritos" :key="site.id"> 
                <a :href="site.link">{{ site.nome }}</a>
            </li>
        </ul>
    </div>
</template>

<script>
export default {
    name: 'SitesFavoritos',
    data() {
        return {
            sitesFavoritos: [
                {   
                    id: 1,
                    nome: 'Google',
                    link: 'google.com'
                },
                {
                    id: 2,
                    nome: 'Google',
                    link: 'google.com'
                },
                {
                    id: 3,
                    nome: 'Google',
                    link: 'google.com'
                }
            ]
        }
    }
}
</script>

<style scoped>

</style>