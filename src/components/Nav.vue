<template>
<div class="main-banner bg bg1" id="home">
    <header class="header">
        <div class="container-fluid px-lg-5">
            <nav class="py-4">
                <div id="logo">
                    <h1>
                        <a href="index.html" class="editContent">
                            DjangoMovie
                        </a>
                    </h1>
                </div>
                <label for="drop" class="toggle">Menu</label>
                <input type="checkbox" id="drop">
                <ul class="menu mt-2">
                    <li class="active"><a href="#">Главная</a></li>
                    <li>
                        <label for="drop-2" class="toggle">Категории <span class="fa fa-angle-down" aria-hidden="true" ></span> </label>
                        <a href="#">
                            Категории 
                            <span class="fa fa-angle-down" aria-hidden="true"></span>
                        </a>
                        <input type="checkbox" id="drop-2">
                        <ul>
                            <li><a href="#">Фильмы</a></li>
                            <li><a href="#">Сериалы</a></li>
                            <li><a href="#">Мультфильмы</a></li>
                        </ul>
                    </li>
                    <li><a href="#" class="login">Вход</a></li>
                </ul>
            </nav>
        </div>
    </header>
    <div class="banner-info">
        <p class="editContent" >лучший сайт на django 3</p>
        <h3 class="mb-4 editContent">Все о кино</h3>
        <div class="ban-buttons">
        </div>
    </div>
</div>
</template>


<script>
    export default {
        name: "Nav"
    }

</script>

<style scoped>
    #home {
        background-color: rgba(0, 0, 0, 0);
        margin-top: 0px;
        background-image: url(../assets/single-post-pic.jpg);
    }

    .editContent {
        outline: none;
        outline-offset: -2px;
        cursor: inherit;
        color: rgb(255, 255, 255);
        font-size: 40px;
        background-color: rgba(0, 0, 0, 0);
        font-family: Source Sans Pro, sans-serif;
    }

    .login{
        color: rgb(255, 255, 255);
        font-weight: 700;
        text-transform: uppercase;
    }
</style>