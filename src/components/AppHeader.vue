<script>
import AppLogo from './AppLogo.vue';

export default {
    name: 'AppHeader',
    components: {
        AppLogo

    },
    data() {
        return{
            links: [
                {
                    label: 'CHARACTERS',
                    url: '#',
                    active: false,
                },
                {
                    label: 'COMICS',
                    url: '#',
                    active: true,
                },
                {
                    label: 'MOVIES',
                    url: '#',
                    active: false,
                },
                {
                    label: 'TV',
                    url: '#',
                    active: false,
                },
                {
                    label: 'GAMES',
                    url: '#',
                    active: false,
                },
                {
                    label: 'COLLECTIBLES',
                    url: '#',
                    active: false,
                },
                {
                    label: 'VIDEOS',
                    url: '#',
                    active: false,
                },
                {
                    label: 'FANS',
                    url: '#',
                    active: false,
                },
                {
                    label: 'NEWS',
                    url: '#',
                    active: false,
                },
                {
                    label: 'SHOP',
                    url: '#',
                    active: false,
                }
            ]
        }
    }
}

</script>

<template>
    
    <header>

        <div>
            <AppLogo/>
        </div>

        <ul>
            <li v-for="link in links">
                <a :href="link.url" :class="{
                    active: link.active == true
                }">
                    {{link.label}}
                </a>
            </li>
        </ul>
    </header>

</template>

<style lang="scss" scoped>
header{
    display: flex;
    align-items: center;
    justify-content: space-between;
    height: 140px;
    background-color: white;
    padding-left: 170px;
    padding-right: 170px;
}
div{
    text-align: center;
}

ul{
    display: flex;
    align-items: center;
    justify-content: center;
    list-style: none;

    li{
        a{
            display: inline-block;
            padding: 15px;
            font-weight: bold;
            text-decoration: none;
            color: black;

        &.active{
            color: #1A84F9;
            text-decoration: underline;
            text-decoration-color: #0282F9;
            text-decoration-thickness: 6px;
        }
        }
    }
}
</style>