<script>

</script>
<main>
    <div class="box">
        <div class="amazing">
            <img class="amazingTypo" src="./pics/amazing-typo.svg" alt="">
            <img class="general" src="./pics/General.png" alt="">
            <h3> مشاهده همه‌</h3>
        </div>
        <div class="wares">
            <div class="ware">
                <img src="./pics/imgCable.jpg" alt="">
                <h3>229,000 T</h3>
            </div>
            <div class="ware">
                <img src="./pics/imgChair.jpg" alt="">
                <h3>3,750,000 T</h3>
            </div>
            <div class="ware">
                <img src="./pics/imgBag.jpg" alt="">
                <h3>469,000 T </h3>
            </div>
            <div class="ware">
                <img src="./pics/imgWalet.jpg" alt="">
                <h3>589,000 T</h3>
            </div>
            <div class="ware">
                <img src="./pics/imgNothing.jpg" alt="">
                <h3>2,730,000 T</h3>
            </div>
            <div class="ware">
                <img src="./pics/imgShoe.jpg" alt="">
                <h3>269,000 T</h3>
            </div>
            <!-- <div class="ware">
                <img src="imgShirt.jpg" alt="">
                <h3>149,000 T</h3>
            </div> -->
        </div>
    </div>

</main>
<style>
    @font-face {
    font-family: myFirstFont;
    src:url('/Yekan.ttf');
    }
    .box{
        background: #ef394e;
        width: 80vw;
        position: relative;
        left: 9%;
        height: 280px;
        border-radius: 15px;
        display: flex;
        flex-direction: row-reverse;
    }
    .amazing{
        display: flex;
        flex-direction: column;
        justify-content:center;
        text-align: center;
        align-items:flex-end;
        position: relative;
        right: 40px;
        padding-top: 25px;
        padding-bottom:25px ;
        /* width: 250px; */

    }
    .amazing .amazingTypo{
        width: 35%;
        position: relative;
        right: 20px;
        cursor: pointer;

    }
    .amazing .general{
        width: 50%;
        cursor: pointer;

    }
    .amazing h3{
        color: #fff;
        font-size: 16px;
        font-family: myFirstFont;
        position: relative;
        right: 20px;
        cursor: pointer;
    }
    .wares{
        display: flex;
        flex-direction: row-reverse;
        /* padding-right: 100px; */
    }

    .ware{
        display: flex;
        flex-direction: column;
        margin-left: 3px;
        background: #fff;
        width: 170px;
        height: 230px;
        position: relative;
        top: 25px;
        justify-content: center;
        align-items: center;
        cursor: pointer;

    }
    .ware:first-child {
        border-radius: 0px 10px 10px 0px;
    }
    .ware:last-child{
        border-radius: 10px 0px 0px 10px;
    }
    .ware img{
        width: 90%;
    }
    .ware h3{
        margin-top: 10px;
        display: flex;
        position: relative;
        right: 30px;

    }


</style>