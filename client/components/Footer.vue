<template>
    <footer>
        <div class="container">
            <ContactsBlock />
            <div class="extra">
                <div class="extra__about">
                    <router-link class="navbar__item" to="/about">О нас</router-link>
                    <router-link class="navbar__item" to="/payment">Оплата</router-link>
                    <router-link class="navbar__item" to="/delivery">Доставка</router-link>
                    <router-link class="navbar__item" to="/contacts">Контакты</router-link>
                </div>
                <div class="extra__contacts">
                    <span>85114 г.Константиновка</span>  <br>
                    <span>ул.Интернациональная 442</span> <br>
                    <br>
                    <span>absolutfam@gmail.com</span>
                    
                </div>
                <div class="extra__socials">
                    <a href="#" class="fb" target="blank"></a>
                    <a href="#" class="vk" target="blank"></a>
                    <a href="#" class="tw" target="blank"></a>
                    <a href="#" class="gl" target="blank"></a>
                    <a href="#" class="yt" target="blank"></a>
                </div>
            </div>
            <div class="copyright">Фабрика мебели "Абсолют" &#169; 1999-2021</div>
        </div>
    </footer>
</template>

<style>
    footer{
        background-blend-mode: multiply;
        background: url(../static/footer.jpg);
        background-color: rgba(159, 98, 18, 0.3);
    }
    footer a{
        color: #fff;
    }
    footer .navbar__item{
        padding-right: 5px;
    }
    footer .navbar__item:hover{
        color: #ebdfcf;
    }
    .extra {
        display: flex;
        justify-content: space-between;
        align-items: center;
        width: 100%;
        color: #fff;
        font-weight: 500;
    }
    .extra__about {
        display: flex;
        flex-direction: column;
        width: 30%;
    }
    .extra__socials a{
        display: inline-block;
        width: 33px;
        height: 33px;
        margin: 2px;  
    }
    .extra__socials {
        height: 33px;
        width: 30%;
        display: flex;
        justify-content: flex-end;
    }
    .fb{
        background: url(../static/socials/fb.png) no-repeat 50% 50%;
    }
    .vk{
        background: url(../static/socials/vk.png) no-repeat 50% 50%;
    }
    .tw{
        background: url(../static/socials/tw.png) no-repeat 50% 50%;
    }
    .gl{
        background: url(../static/socials/gl.png) no-repeat 50% 50%;
    }
    .yt{
        background: url(../static/socials/yt.png) no-repeat 50% 50%;
    }
    .copyright{
        font-weight: 200;
        width: 100%;
        text-align: center;
        color: #fff;
        padding: 10px 0;
    }
</style>