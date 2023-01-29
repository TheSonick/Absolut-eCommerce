<template>
    <div class="categories__list list">
        <router-link class="list__item" to="/about">
            <img width="44px" src="@/static/icons/cabinets-mini.svg" alt="cabinets-mini Absolut">
            Шкафы
        </router-link>
        <router-link class="list__item" to="/payment">
            <img width="44px" src="@/static/icons/tables-mini.svg" alt="tables-mini Absolut">
            Столы
        </router-link>
        <router-link class="list__item" to="/delivery">
            <img width="44px" src="@/static/icons/dressers-mini.svg" alt="dressers-mini Absolut">
            Комоды
        </router-link>
        <router-link class="list__item" to="/contacts">
            <img width="44px" src="@/static/icons/stands-mini.svg" alt="stands-mini Absolut">
            Тумбы
        </router-link>
    </div>
</template>

<style scoped>
    .categories__list {
        display: none;
        border-radius: 4px;
        background-color: #fff;
        position: absolute;
        text-align: left;
        box-shadow: 0 2px 4px rgb(0 0 0 / 12%);
        padding-top: 10px;
        top: 100%;
        left: -25%;
        justify-content: center;
    }
    .list__item{
        display: flex;
        width: 100%;
        align-items: center;
        font-size: 14px;
        border-radius: 4px;
        letter-spacing: 1px;
        padding: 6px 18px;
        font-weight: 600;
        color: #9f6212;
    }
    .list__item:first-child{
        border-top: 2px solid #9f6212;
    }
    .list__item:last-child{
        border-bottom: 0;
    }

    .list__item:hover{
        background-color: #ebdfcf;
    }
    .list__item img{
        padding: 6px;
        margin-right: 6px;
    }
</style>