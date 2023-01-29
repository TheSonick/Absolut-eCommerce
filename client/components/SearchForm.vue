<template>
    <div class="search-block">
		<div class="search">			
            <form role="search" method="get" class="search__form" >
                <input type="search" class="search__input" placeholder="Поиск мебели тут">
                <input type="submit" class="search__submit">
            </form>
        </div>
    </div>
</template>

<style scoped>
    .search-block{
        max-width: 12%;
    }
    .search__form {
        display: flex;
        flex-flow: row wrap;
        align-items: center;
        position: relative;
    }
    .search__input{
        display: inline-block;
        width: 100%;
        height: 44px;
        color: #9f6212;
        border: none;
        outline: none;
        font-weight: 600;
        padding: 3px 24px 3px 3px;
    }
    .search__input::placeholder{
        color: #9f6212;
    }
    .search__input::-ms-clear {
        width : 0;
        height: 0;
    }
    .search__submit{
        cursor: pointer;
        border: none;
        background: url(..\static\UI\loop.svg) no-repeat;
        background-size: 21px 21px;
        background-position-y: 13px;
        font-size: 0;
        padding: 0;
        position: absolute;
        right: 0;
        top: -1px;
        height: 100%;
        width: 21px;
    }
    input::-webkit-search-decoration,
    input::-webkit-search-cancel-button,
    input::-webkit-search-results-button,
    input::-webkit-search-results-decoration { display: none; }
</style>