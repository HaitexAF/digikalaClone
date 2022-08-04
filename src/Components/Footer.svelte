<script>

</script>
<footer>
    <div class="head">
        <div class="digi">
            <img src="./pics/digiPersian.svg" alt="">
        </div>
        <div class="backUp">
            <button>
                بازگشت به بالا
                <img src="./pics/footerUp.png" alt="">
            </button>
        </div>
    </div>
    <div class="phoneNumber">
        <div>
            تلفن پشتیبانی ۶۱۹۳۰۰۰۰ – ۰۲۱
        </div>
        <div>|</div>
        <div>
             هفت روز هفنه، ۲۴ ساعته پاسخگوی شما هستیم
        </div>
    </div>
    <div class="items">
        <div class="item">
            <img src="./pics/express-delivery.svg" alt="">
            <p>
                امکان تحویل اکسپرس
            </p>
        </div>
        <div class="item">
            <img src="./pics/cash-on-delivery.svg" alt="">
            <p>
                امکان پرداخت در محل
            </p>
        </div>
        <div class="item">
            <img src="./pics/support.svg" alt="">
            <p>
                هفت روز هفته، ۲۴ ساعته
            </p>
        </div>
        <div class="item">
            <img src="./pics/days-return.svg" alt="">
            <p>
                هفت روز ضمانت بازگشت کالا
            </p>
        </div>
        <div class="item">
            <img src="./pics/original-products.svg" alt="">
            <p>
                ضمانت اصل بودن کالا
            </p>
        </div>

    </div>
    <div class="menu">
        <div class="withDg">
            <h3>
                ‌با دیجی‌کالا
            </h3>
            <h4>
                اتاق خبر دیجی‌کالا
            </h4>
            <h4>
                فروش در دیجی‌کالا
            </h4>
            <h4>
                فرصت های شغلی
            </h4>
            <h4>
                تماس با دیجی‌کالا
            </h4>
            <h4>
                درباره دیجی‌کالا
            </h4>


        </div>
        <div class="services">
            <h3>
                خدمات مشتریان
            </h3>
            <h4>
                پاسخ به پرسشهای متداول
            </h4>
            <h4>
                رویه های بازگرداندن کالا
            </h4>
            <h4>
                شرایط استفاده
            </h4>
            <h4>
                حریم خصوصی
            </h4>
            <h4>
                گزارش باگ
            </h4>


        </div>
        <div class="guide">
            <h3>راهنمای خرید از دیجی‌کالا</h3>
            <h4>
                نحوه ثبت سفارش
            </h4>
            <h4>
                رویه ارسال سفارش
            </h4>
            <h4>
                شیوه های پرداخت
            </h4>
        </div>
        <div class="withUs">
            <h3>
                همراه ما باشید
            </h3>
            <div class="icons">
                <img src="./pics/footerInstagram.png" alt="">
                <img src="./pics/footerTwitter.png" alt="">
                <img src="./pics/footerLinkedin.png" alt="">
                <img src="./pics/footerAparat.png" alt="">

            </div>
            <h3>
                با ثبت ایمیل، از جدیدترین تخفیف ها باخبر شوید
            </h3>
            <div>
                <button>ثبت</button>
                <input type="text" placeholder="ایمیل شما" >
            </div>


        </div>

    </div>
</footer>
<style>
    @font-face {
    font-family: myFirstFont;
    src:url('/Font/BYekan.ttf');
    }
    footer{
        margin: 2% 0%;
        border-top: 1px solid rgba(128, 128, 128, 0.29);
        font-family: myFirstFont;

    }
    .head{
        display: flex;
        flex-direction: row-reverse;
        justify-content: space-between;
        margin: 30px 2% 0px 2%;
    }
    .backUp button {
        display: flex;
        flex-direction: row-reverse;
        align-items: center;
        text-align: center;
        justify-content: center;
        background: #fff;
        font-family: myFirstFont;
        border: 1px solid rgba(0, 0, 0, 0.251);
        border-radius: 10px;
        font-size: 15px;
        padding-right: 5px;
        gap: 10px;
        opacity: 70%;
        height: 50px;
        cursor: pointer;
    }
    .backUp button img{
        width: 20%;
    }
    .phoneNumber{
        display: flex;
        flex-direction: row-reverse;
        justify-content: end;
        margin: 0% 2%;
        gap: 10px;
    }
    .items{
        display: flex;
        flex-direction: row-reverse;
        justify-content: center;
        gap: 200px;
        text-align: center;
        margin-top: 40px;
        font-size: 14px;
    }
    .menu{
        display: flex;
        flex-direction: row-reverse;
        justify-content: center;
        text-align: end;
        gap: 270px;
        line-height: 35px;
        margin-top: 20px;
    }
    .menu h3{
        opacity: 80%;
        font-size: 20px;
    }
    .menu h4{
        opacity: 50%;
        font-size: 17px;
    }
    .withUs button{
        width: 60px;
        height: 45px;
        border-radius: 10px;
        background: rgb(204, 204, 204);
        border: none;
        color: #fff;
        font-family: myFirstFont;
        font-size: large;
        font-weight: bold;
        cursor: pointer;
        margin-top: 15px;
    }
    .withUs .icons{
        display: flex;
        flex-direction: row-reverse;
        gap: 35px;
        align-items: flex-end;
        margin-top: 15px;
        /* width: 10px; */
        /* height: 10px; */
        /* width: 5%; */
    }
    .withUs .icons img:nth-child(4){
        width: 35px;
    }
    .withUs input{
        height: 45px;
        width: 250px;
        border-radius: 10px;
        border: none;
        background: rgb(219, 219, 219);
        text-align: end;
        font-family: myFirstFont;
        font-size: 20px ;
        padding-right: 10px;
    }
</style>