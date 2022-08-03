
<li>
    <div class="rightLists">
        <div>
            <ul class="category">
                <h5> دسته‌بندی کالاها</h5>
                <img src="./pics/List.png" alt="">
            </ul>
        </div>
        <div>
            <ul>
                <h5>سوپرمارکت</h5>
                <img src="./pics/market.png" alt="">
            </ul>
        </div>
        <div>
            <ul>
                <h5>پرفروش ترین‌ها</h5>
                <img src="./pics/fire.png" alt="">
            </ul>
        </div>
        <div>
            <ul>
                <h5> تخفیف‌ها و پیشنهادها</h5>
                <img src="./pics/discount.png" alt="">
            </ul>
        </div>
        <div>
            <ul class="amazing">
                <h5> شگفت‌ا‌نگیزها</h5>
                <img src="./pics/amazing.png" alt="">
            </ul>
        </div>
        <div>
            <ul>
                <h5>سوالی دارید؟</h5>
            </ul>
        </div>
        <div>
            <ul>
                <h5>‌! فروشنده شوید</h5>
            </ul>
        </div>
    </div>
    <div>
        <div>
            <ul class="location">
                <h5>شهر خود را انتخاب کنید</h5>
                <img src="./pics/location.png" alt="">
            </ul>

        </div>
    </div>

</li>

<style>
    @font-face {
    font-family: myFirstFont;
    src:url('/Far.Roya.ttf');
    }
    li{
        display: flex;
        flex-direction:row-reverse;
        justify-content: space-between;
    }
    .rightLists{
        display: flex;
        flex-direction: row-reverse;
        justify-content: space-between;
        /* padding-right: 10px; */
    }
    ul{
        display: flex;
        padding-right: 10px;
        cursor: pointer;
    }
    img{
        width: 15px;
    }
    .location{
        padding-left: 15px;
    }
    h5{
        margin-right: 5px;
        font-size: 15px;
        /* font-weight: bold; */
        opacity: 70%;
        font-family: myFirstFont;
    }
    .category h5{
        font-size: 15px;
        font-weight: 900;
        opacity: 100%;
        border-left: 1px solid lightgrey;
        padding-left: 10px;
    }
    .amazing {
        border-left: 1px solid lightgrey;
        padding-left: 10px;
    }
</style>