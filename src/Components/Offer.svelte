<script>

</script>
<main>
    <div class="offer">
        <div>
            <h1>پیشنهاد دیجی‌کالا</h1>
        </div>
        <div class="items">
            <div class="item">
                <img src="./pics/offerPowerbank.jpg" alt="">
                <h3>پاوربانک</h3>
            </div>
            <div class="item">
                <img src="./pics/offerSpeaker.jpg" alt="">
                <h3>
                    اسپیکر
                </h3>
            </div>
            <div class="item">
                <img src="./pics/offerSocks.jpg" alt="">
                <h3>
                    جوراب مردانه
                </h3>
            </div>
            <div class="item">
                <img src="./pics/offerLaptop.jpg" alt="">
                <h3>
                    لپ‌تاپ و الترابوک
                </h3>
            </div>
            <div class="item">
                <img src="./pics/offerHeadphone.jpg" alt="">
                <h3>
                    هدفون و هدست
                </h3>
            </div>
            <div class="item">
                <img src="./pics/offerPhone.avif" alt="">
                <h3>
                    گوشی موبایل
                </h3>
            </div>
            <div class="item">
                <img src="./pics/offerConsole.jpg" alt="">
                <h3>
                    کنسول خانگی
                </h3>
            </div>
            <div class="item"> 
                <img src="./pics/offerCpuCooler.jpg" alt="">
                <h3>
                    خنک کننده پردازنده
                </h3>
            </div>
            <div class="item">
                <img src="./pics/offerCharger.jpg" alt="">
                <h3>
                    شارژر تبلت و موبایل
                </h3>
            </div>
            <div class="item">
                <img src="./pics/offerSmartWatch.jpg" alt="">
                <h3>
                    ساعت هوشمند
                </h3>
            </div>
            <div class="item">
                <img src="./pics/offerChargeCable.jpg" alt="">
                <h3>
                    کابل شارژ و مبدل
                </h3>
            </div>
            <div class="item">
                <img src="./pics/offerMouse.jpg" alt="">
                <h3>
                    ماوس
                </h3>
            </div>
        </div>
    </div>
</main>
<style>
    @font-face {
    font-family: myFirstFont;
    src:url('/Yekan.ttf');
    }
    .offer{
        display: grid;
        justify-content: center;
        text-align: center;
        align-items: center;
        margin-top: 45px;
    }
    .items{
        display: grid;
        grid-template-columns: repeat(6, 200px);
        grid-template-rows: repeat(2 , 10vw);
        /* gap: 1px solid black; */
        margin-top: 30px;
        border: 1px solid rgba(0, 0, 0, 0.358);
        height: 350px;
        border-radius: 15px;
        background: rgba(211, 211, 211, 0.106);

    }
    .item{
        cursor: pointer;
    }
    .item img{
        width: 80px;
        height: 80px;
        border-radius: 50%;
        margin-top: 40px;
    }
    .item h3{
        font-family: myFirstFont;
        font-size: 15px;
    }
</style>
