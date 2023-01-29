<template>
    <div class="activities">
        <div class="sign-in"></div>
        <div class="user"></div>
        <div class="sign-out"></div>
        <div class="heart"></div>
        <div class="cart"></div>
    </div>
</template>

<style scoped>
    .activities{
        display: flex;
        align-items: center;
        justify-content: flex-end;
    }
    .sign-in, .sign-out, .user, .heart, .cart{
        cursor: pointer;
        padding: 20px;
        border-radius: 4px;
        height: 24px;
        width: 24px;
        transition: .3s ease;
    }
    .sign-out{
        display: block;
        background: url(..\static\UI\sign-out.svg) no-repeat center;
        background-size: 24px;
    }
    .sign-in{
        background: url(..\static\UI\sign-in.svg) no-repeat center;
        background-size: 24px;
    }
    .user{
        display: block;
        background: url(..\static\UI\user.svg) no-repeat center;
        background-size: 24px;
    }
    .cart{
        position: relative;
        background: url(..\static\UI\cart.svg) no-repeat center;
        background-size: 24px;
    }
    .heart{
        position: relative;
        background: url(..\static\UI\heart.svg) no-repeat center;
        background-size: 24px;
    }
    .cart::after{
        content: "1";
        display: block;
        position: absolute;
        right: 1px;
        top: 1px;
        text-align: center;
        font-size: 10px;
        font-weight: 600;
        width: 18px;
        height: 18px;
        padding: 1px;
        color: #fff;
        background-color: #9f6212;
        border: 2px solid #fff;
        border-radius: 4px;
        transition: .3s ease;
    }
    .heart::after{
        content: "1";
        display: block;
        position: absolute;
        right: 1px;
        top: 1px;
        text-align: center;
        font-size: 10px;
        font-weight: 600;
        width: 18px;
        height: 18px;
        padding: 1px;
        color: #fff;
        background-color: #9f6212;
        border: 2px solid #fff;
        border-radius: 4px;
        transition: .3s ease;
    }
    .heart:hover::after, .cart:hover::after{
        border-color: #ebdfcf;
        color: #ebdfcf;
    }
    .sign-in:hover, .sign-out:hover, .user:hover, .heart:hover, .cart:hover{
        background-color: #ebdfcf;
    }
</style>