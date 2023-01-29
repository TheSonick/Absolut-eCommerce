<template>
    <div class="categories">
        <router-link class="categories__item" to="/products">
            <img width="124px" src="@/static/icons/cabinets.svg" alt="cabinets Absolut">
            <span class="categories__title">Шкафы</span>
        </router-link>
        <router-link class="categories__item" to="/products">
            <img width="124px" src="@/static/icons/tables.svg" alt="tables Absolut">
            <span class="categories__title">Столы</span>
        </router-link>
        <router-link class="categories__item" to="/products">
            <img width="124px" src="@/static/icons/dressers.svg" alt="dressers Absolut">
            <span class="categories__title">Комоды</span>
        </router-link>
        <router-link class="categories__item" to="/products">
            <img width="124px" src="@/static/icons/stands.svg" alt="stands Absolut">
            <span class="categories__title">Тумбы</span>
        </router-link>
        <!-- <router-link class="categories__item" to="/delivery">
            <img width="124px" src="@/static/icons/dressers.svg" alt="dressers Absolut">
            <span class="categories__title">Комоды</span>
        </router-link>
        <router-link class="categories__item" to="/about">
            <img width="124px" src="@/static/icons/cabinets.svg" alt="cabinets Absolut">
            <span class="categories__title">Шкафы</span>
        </router-link>
        <router-link class="categories__item" to="/contacts">
            <img width="124px" src="@/static/icons/stands.svg" alt="stands Absolut">
            <span class="categories__title">Тумбы</span>
        </router-link>
        <router-link class="categories__item" to="/payment">
            <img width="124px" src="@/static/icons/tables.svg" alt="tables Absolut">
            <span class="categories__title">Столы</span>
        </router-link> -->
    </div>
</template>

<style scoped>
    .categories {
        display: grid;
        min-height: calc(100vh - 60px - 392px - 20px - 160px);
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
        padding: 10px 10px 7px 10px;
        border-radius: 6px;
        border: 2px solid #cdb483;
        text-align: center;
        font-size: 20px;
        font-weight: 600;
        color: #9f6212;
        background-color: #fff;
        transition: .3s ease;
    }
    .categories__item img{
        padding: 10px;
    }
    .categories__item:hover{
        box-shadow: 0 2px 4px rgb(159 98 18 / 12%);
        border-color: #fff;
    }
    .categories__title{
        width: 100%;
        padding: 10px 0;
    }
</style>