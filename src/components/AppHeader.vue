<script>
import AppLogo from './AppLogo.vue';

export default {
    name: 'AppHeader',
    components: {
        AppLogo
    }
}

</script>

<template>

    <header>

        <div>
            <AppLogo/>
        </div>

        <ul>
            <li>
                <a href="">
                    CHARACTERS
                </a>
            </li>
            <li class="">
                <a href="" class="active">
                    COMICS
                </a>
            </li>
            <li>
                <a href="">
                    MOVIES
                </a>
            </li>
            <li>
                <a href="">
                    TV
                </a>
            </li>
            <li>
                <a href="">
                    GAMES
                </a>
            </li>
            <li>
                <a href="">
                    COLLECTIBLES
                </a>
            </li>
            <li>
                <a href="">
                    VIDEOS
                </a>
            </li>
            <li>
                <a href="">
                    FANS
                </a>
            </li>
            <li>
                <a href="">
                    NEWS
                </a>
            </li>
            <li>
                <a href="">
                    SHOP
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