<script>

</script>
<div class="box">
    <div class="amazing">
        <img class="amazingTypo" src="./pics/amazing-typo.svg" alt="">
        <img class="general" src="./pics/General.png" alt="">
        <div class="watchMore">
            <img src="./pics/moreThanWhite.png" alt="">
            <h3> مشاهده همه‌</h3>

        </div>
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
<style>
    @font-face {
    font-family: myFirstFont;
    src:url('/Yekan.ttf');
    }
    .box{
        background: #ef394e;
        /* width: 100%; */
        /* position: relative; */
        /* left: 9%; */
        height: 280px;
        margin: 1% 10%;
        border-radius: 15px;
        display: flex;
        justify-content: center;
        flex-direction: row-reverse;
        /* flex-basis: 600px; */
    }
    .amazing{
        display: flex;
        /* flex-direction: column; */
        justify-content:center;
        align-items:center;
        text-align: center;
        flex-flow: column;
        padding: 1% 2%;
        /* text-align: center; */
        /* align-items:flex-end; */
        /* position: relative; */
        /* right: 40px; */
        /* padding-top: 25px; */
        /* padding-bottom:25px ; */
        /* width: 250px; */

    }
    .amazing .amazingTypo{
        width: 55%;
        /* position: relative; */
        /* right: 20px; */
        cursor: pointer;
        /* justify-content:end; */


    }
    .amazing .general{
        width: 60%;
        cursor: pointer;

    }
    .amazing h3{
        color: #fff;
        font-size: 16px;
        font-family: myFirstFont;
        /* position: relative;
        right: 10px; */
    }
    .watchMore{
        display: flex;
        flex-direction: row;
        cursor: pointer;

    }
    .watchMore img{
        width:12%;
        height: 80%;
        margin-right: 3px;
        margin-top: 3px;
        /* height: 50%; */
    }
    .wares{
        display: flex;
        flex-direction: row-reverse;
        margin-left: 10px;
        /* justify-content: center; */

        /* padding-right: 100px; */
    }

    .ware{
        display: flex;
        flex-direction: column;
        margin:25px 3px;
        /* padding: 10% 1%; */
        background: #fff;
        width: 170px;
        height: 230px;
        /* position: relative; */
        /* top: px; */
        justify-content: center;
        align-items: center;
        /* padding-top: auto; */
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