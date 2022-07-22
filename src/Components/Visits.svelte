<script>

</script>
<main>
    <div class="box">
        <div class="part">
            <div class="text">
                <h4>
                    ساعت هوشمند
                </h4>
                <p>
                    بر اساس بازدیدهای شما
                </p>
            </div>
            <div class="imgs">
                <img src="./pics/vSwatch1.jpg" alt="">
                <img src="./pics/vSwatch2.jpg" alt="">
                <img src="./pics/vSwatch3.jpg" alt="">
                <img src="./pics/vSwatch4.jpg" alt="">
            </div>
            <div class="more">
                <p >
                    مشاهده
                </p>
            </div>



        </div>
        <div class="part">
            <div class="text">
                <h4>
                    هدفون، هدست و هندزفری
    
                </h4>
                <p>
                    بر اساس بازدیدهای شما
                </p>
            </div>
            <div class="imgs">
                <img src="./pics/vHeadphone1.jpg" alt="">
                <img src="./pics/vHeadphone2.jpg" alt="">
                <img src="./pics/vHeadphone3.jpg" alt="">
                <img src="./pics/vHeadphone4.jpg" alt="">
            </div>
            <div class="more">
                <p >
                    مشاهده
                </p>
            </div>



        </div>
        <div class="part">
            <div class="text">
                <h4>
                    کیف و کاور گوشی
                </h4>
                <p>
                    بر اساس بازدیدهای شما
                </p>
            </div>
            <div class="imgs">
                <img src="./pics/vCover1.jpg" alt="">
                <img src="./pics/vCover2.jpg" alt="">
                <img src="./pics/vCover3.jpg" alt="">
                <img src="./pics/vCover4.jpg" alt="">
            </div>
            <div class="more">
                <p>
                    مشاهده
                </p>
            </div>



        </div>
        <div class="part">
            <div class="text">
                <h4>
                    گوشی موبایل
                </h4>
                <p>
                    بر اساس بازدیدهای شما
                </p>
            </div>
            <div class="imgs">
                <img src="./pics/vPhone1.jpg" alt="">
                <img src="./pics/vPhone2.jpg" alt="">
                <img src="./pics/vPhone4.jpg" alt="">
                <img src="./pics/vPhone3.jpg" alt="">
            </div>
            <div class="more">
                <p>
                    مشاهده
                </p>
            </div>



        </div>
    </div>
</main>
<style>
    @font-face {
    font-family: myFirstFont;
    src:url('/Yekan.ttf');
    }
    .box{
        width: 1300px;
        height: 420px;
        display: flex;
        /* padding: 10px 220px; */
        margin-top: 40px;
        padding: 0px 20px;
        border: 1px solid lightgray;
        border-radius: 15px;
        position: relative;
        left: 160px;
    }
    .part{
        width: 325px;
        height: 420px;
        display: grid;
        text-align: right;
        align-items:flex-end;
    }
    .part:nth-child(2){
        border-right:1px solid lightgray;
        border-left:1px solid lightgray;
    }
    .part:nth-child(3){
        border-right:1px solid lightgray;
        margin-left: 20px;
    }
    .part:nth-child(4){
        margin-left: 30px;
    }
    .part .imgs{
        display: grid;
        grid-template-columns:repeat(2 , 146px);
        grid-template-rows: repeat(2 , 140px);
        /* position: relative; */
        cursor: pointer;
    }

    /* img:nth-child(1){
        border-right: 1px solid lightblue;
        border-bottom: 1px solid lightblue;
        margin-bottom: 10px;

        padding-right: 10px; 
    }
    img:nth-child(3){
        border-right: 1px solid lightblue;
        padding-right: 10px;

    } */
    .part .text{
        position: relative;
        right: 10px;
        font-family: myFirstFont;
        margin-bottom: 20px;

    }
    .text p{
        font-weight: 100;
        margin-top: 5px;
    }
    .part img{
        width: 125px;
        height: 125px;
    }
    .more{
        text-align: center;
        color: rgb(0, 144, 144);
        cursor: pointer;
        margin-bottom: 10px;
        font-family: myFirstFont;

    }
</style>