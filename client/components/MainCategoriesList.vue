<template>
    <div class="categories">
        <router-link class="categories__item" to="/about">
            <img width="124px" src="@/static/icons/cabinets.svg" alt="cabinets Absolut">
            <span>Шкафы</span>
        </router-link>
        <router-link class="categories__item" to="/payment">
            <img width="124px" src="@/static/icons/tables.svg" alt="tables Absolut">
            <span>Столы</span>
        </router-link>
        <router-link class="categories__item" to="/delivery">
            <img width="124px" src="@/static/icons/dressers.svg" alt="dressers Absolut">
            <span>Комоды</span>
        </router-link>
        <router-link class="categories__item" to="/contacts">
            <img width="124px" src="@/static/icons/stands.svg" alt="stands Absolut">
            <span>Тумбы</span>
        </router-link>
        <!-- <router-link class="categories__item" to="/delivery">
            <img width="124px" src="@/static/icons/dressers.svg" alt="dressers Absolut">
            <span>Комоды</span>
        </router-link>
        <router-link class="categories__item" to="/about">
            <img width="124px" src="@/static/icons/cabinets.svg" alt="cabinets Absolut">
            <span>Шкафы</span>
        </router-link>
        <router-link class="categories__item" to="/contacts">
            <img width="124px" src="@/static/icons/stands.svg" alt="stands Absolut">
            <span>Тумбы</span>
        </router-link>
        <router-link class="categories__item" to="/payment">
            <img width="124px" src="@/static/icons/tables.svg" alt="tables Absolut">
            <span>Столы</span>
        </router-link> -->
    </div>
</template>

<style scoped>
    .categories {
        display: grid;
        grid-template-columns: 1fr 1fr 1fr 1fr;
        row-gap: 10px;
        column-gap: 10px;
        width: 100%;
    }
    .categories__item{
        display: flex;
        justify-content: center;
        flex-wrap: wrap;
        align-items: center;
        height: 1fr;
        padding: 10px 10px 7px 10px;
        border-radius: 4px;
        border: 2px solid #fff;
        text-align: center;
        font-size: 20px;
        font-weight: 600;
        background-color: #fff;
        color: #9f6212;
        transition: .3s ease;
    }
    .list__item:last-child{
        border-bottom: 0;
    }
    .categories__item img{
        padding: 10px;
    }
    .categories__item:hover{
        background-color: #ebdfcf;
        border-color: #9f6212;
    }
    .categories__item span{
        width: 100%;
        padding: 10px 0;
    }
</style>