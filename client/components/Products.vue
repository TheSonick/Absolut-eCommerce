<template>
    <div class="right">
        <div class="wrapper">
            <h3>Товары</h3>
            
            <div class="sorting_box">
                <label for="sorting">Сортировать:</label>
                <select class="select" id="sorting">
                    <option value="priceUp">От дешевых к дорогим</option>
                    <option value="priceDown">От дорогих к дешевым</option>
                </select>
            </div>
        </div>
        <div class="products">
            <div class="product__item"></div>
            <div class="product__item"></div>
            <div class="product__item"></div>
            <div class="product__item"></div>
            <div class="product__item"></div>
            <div class="product__item"></div>
            <div class="product__item"></div>
            <div class="product__item"></div>
        </div>
    </div>
</template>

<style scoped>
.right{
    padding: 10px;
}
.sorting_box{
    color:#fff;
    font-weight: 600;
}
.select{
    display: inline-block;
    color: #9f6212;
    border: none;
    outline: none;
    font-weight: 600;
    border-radius:2px;
    padding: 2px;
}
/* option{
    font-weight: 600;
} */
.products{
    display: grid;
    grid-template-columns: 1fr 1fr 1fr 1fr;
    row-gap: 10px;
    column-gap: 10px;
}
.wrapper{
    display: flex;
    align-items: center;
    justify-content: space-between;
}
h3{
    padding: 0 10px 10px 0;
    font-size: 24px;
    font-weight: 600;
}
.product__item{
    height: 300px;
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    align-items: center;
    padding: 10px 10px 7px 10px;
    border-radius: 6px;
    border: 2px solid #ebdfcf;
    text-align: center;
    font-size: 20px;
    font-weight: 600;
    color: #9f6212;
    background-color: #fff;
    transition: .3s ease;
}
.product__item:hover{
    box-shadow: 0 2px 4px rgb(159 98 18 / 12%);
    border-color: #fff;
}
</style>