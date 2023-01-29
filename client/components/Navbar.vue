<template>
    <nav>
        <div class="navbar">
            <router-link class="navbar__item" to="/">
                Продукция
                <NavbarCategoriesList />
            </router-link>
            <router-link class="navbar__item" to="/about">О нас</router-link>
            <router-link class="navbar__item" to="/contacts">Контакты</router-link>
            <router-link class="navbar__item" to="/delivery">Доставка и оплата</router-link>
        </div>
    </nav>
</template>

<style scoped>
    .navbar {
        display: flex;
        padding-top: 1px;
        margin: 0;
    }
    .navbar__item {
        position: relative;
        text-align: center;
        padding: 5px 10px 5px 10px;
        border-radius: 4px;
        color: #9f6212;
        font-size: 16px;
        font-weight: 600;
        transition: .3s ease;
    }
    .navbar__item:first-child {
        padding-left: 31px;
    }
    .navbar__item:first-child::after {
        content: "";
        width: 11px;
        height: 11px;
        border-right: 2px solid #9f6212;
        border-bottom: 2px solid #9f6212;
        position: absolute;
        left: 10px;
        top: 6px;
        transform: rotate(45deg);
        transition: .3s ease;
    }
    .navbar__item:hover {
        background-color: #ebdfcf;
    }
    .navbar__item:hover::after{
        transform: rotate(-135deg);
        top: 12px;
    }
    .navbar__item:hover .categories__list{
        display: flex;
        flex-wrap: wrap;
    }
    
</style>