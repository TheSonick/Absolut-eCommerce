<template>
    <div class="contacts">
        <div class="lang">
            <a href="/">RU</a>
            <span> | </span>
            <a href="/">UK</a>
        </div>
        <div class="info">
            <div class="phones">
                <span> +380 95 501 34 55 </span> <br>
                <span> +380 6272 4 27 72 </span>
                
            </div>
            <div class="working-hours">
                <span> пн-пт: 8:00 - 17:00 </span> <br>
                <span> сб: 8:00 - 14:00 </span>
            </div>
        </div>
        <div class="callback">
            Обратная связь
        </div>
    </div>
</template>

<style>
    .contacts{
        display: flex;
        justify-content: space-between;
        align-items: center;
        width: 100%;
        padding-top: 10px;
        padding-bottom: 0;
        border-bottom: none;
    }
    .lang{
        color: #fff;
        padding-right: 105px;
        font-weight: 600;
    }
    .info{
        display: flex;
        align-items: center;
        justify-content: center;
        margin: 0 auto;
        font-weight: 600;
        color: #fff;
    }
    .phones{
        font-size: 16px;
        padding-right: 10px;
        border-right: 1px solid #fff;
    }
    .working-hours{
        font-weight: 500;
        padding-left: 10px;
    }
    .callback{
        display: flex;
        justify-content: space-between;
        align-items: center;
        cursor: pointer;
        background-color: #fff;
        color: #9f6212;
        border-radius: 4px;
        border: 2px solid #fff;
        font-size: 14px;
        font-weight: 600;
        padding: 10px;
        transition: .3s ease;
    }
    .callback:hover {
        background-color: #ebdfcf;
        border-color: #9f6212;
    }
</style>