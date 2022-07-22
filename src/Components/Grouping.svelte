<script>

</script>
<main>
    <div class="grouping">
        <div>
            <h1>‌دسته‌بندی‌های دیجی‌کالا</h1>
        </div>
        <div class="items">
            <div>
                <img src="./pics/gpToys.png" alt="">
                <h3>اسباب‌بازی, کودک و نوزاد</h3>
            </div>
            <div>
                <img src="./pics/gpSuperMarket.png" alt="">
                <h3>کالاهای سوپرمارکتی</h3>
            </div>
            <div>
                <img src="./pics/gpDress.png" alt="">
                <h3>مد و پوشاک</h3>
            </div>
            <div>
                <img src="./pics/gpTool.png" alt="">
                <h3>ابزار و تجهیزات صنعتی</h3>
            </div>
            <div>
                <img src="./pics/gpDigital.png" alt="">
                <h3>کالاهای دیجیتال</h3>
            </div>
            <div>
                <img src="./pics/gpBooks.png" alt="">
                <h3>کتاب, لوازم‌تحریر و هنر</h3>
            </div>
            <div>
                <img src="./pics/gpKitchen.png" alt="">
                <h3>خانه و آشپزخانه</h3>
            </div>
            <div>
                <img src="./pics/gpBeauty.png" alt="">
                <h3>زیبایی و سلامت</h3>
            </div>
            <div>
                <img src="./pics/gpHandicrafts.png" alt="">
                <h3>محصولات بومی و محلی</h3>
            </div>
            <div>
                <img src="./pics/gpMotor.jpg" alt="">
                <h3>وسایل نقلیه و لوازم یدکی</h3>
            </div>
        </div>

    </div>
</main>
<style>
    @font-face {
    font-family: myFirstFont;
    src:url('/Yekan.ttf');
    }
    .grouping{
        display: grid;
        justify-content: center;
        text-align: center;
        align-items: center;
        margin-top: 20px;
    }
    .items{
        display: grid;
        margin-top: 15px;
        grid-template-columns: repeat(5, 300px);
        grid-template-rows: repeat(2 , 14vw);
        cursor: pointer;
    }
    img{
        width: 50%;
    }
    h3{
        font-family: myFirstFont;


    }

</style>