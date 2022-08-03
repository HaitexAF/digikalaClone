<script>
    import DgClubBar from "./dgClubBar.svelte";


    // export DgClubBar;
</script>
<div class="box">
    <div class="plus">
        <img class="digiplus" src="./pics/digiPlus.svg" alt="">
        <h3>خدمات ویژه برای اعضای دیجی‌پلاس</h3>
        <div class="membership">
            <h4>عضویت</h4>
            <img src="./pics/leftArrow.png" alt="">
        </div>
        <img src="./pics/dpRocket.png"  class="rocket" alt="">

    </div>
    <div class="items">
        <div class="header">
            <div class="send">
                <img src="./pics/dpRocketIcon.png" alt="">
                <h3>ارسال فوری</h3>
            </div>
            <div class="more">
                <p>مشاهده همه</p>
                <img src="./pics/moreThan.png" alt="">
            </div>
        </div>
        <div class="imgs">
            <img src="./pics/dpCable.jpg" alt="">
            <img src="./pics/dpHat.jpg" alt="">
            <img src="./pics/dpHeadphone.jpg" alt="">
            <img src="./pics/dpHeadphone2.jpg" alt="">
            <img src="./pics/dpHeadphone3.jpg" alt="">
            <img src="./pics/dpHeadphone4.jpg" alt="">
            <img src="./pics/dpHolder.jpg" alt="">
            <img src="./pics/dpKnife.jpg" alt="">
            <img src="./pics/dpMachine.jpg" alt="">
            <img src="./pics/dpPad.jpg" alt="">
            <img src="./pics/dpPhone.jpg" alt="">
            <img src="./pics/dpZaeferan.jpg" alt="">

        </div>
    </div>
</div>

<DgClubBar />
<style>
    @font-face {
    font-family: myFirstFont;
    src:url('/Yekan.ttf');
    }
    .box{
        background: rgb(176, 12, 141);
        width: 1300px;
        height: 350px;
        margin:20px 160px;
        border-radius: 15px;
        display: flex;
        flex-direction: row-reverse;
        font-family: myFirstFont;

    }
    .plus{
        padding: 20px;
        margin: 15px 10px;
        width: 300px;
        color: #fff;
        text-align: right;
        line-height: 30px;
    }
    .plus h3{
        font-size: 15px;
    }
    .plus img{
        width: 55%;
    }
    .digiplus{
        cursor: pointer;
    }
    .rocket{
        position: relative;
        top: 40px;
        right: 100px;
    }
   .membership{
        border: 1px solid white;
        display: flex;
        flex-direction: row-reverse;
        width: 100px;
        padding-right: 10px;
        justify-content:right;
        position: relative;
        left: 170px;
        border-radius: 10px;
        cursor: pointer;
    }
    .membership img{
        width: 25px;
        margin-right: 5px;
    }
    .items{
        background: #fff;
        width: 960px;
        height: 320px;
        margin-top: 15px;
        border-radius: 15px;
    }
    .header{
        display: flex;
        flex-direction: row-reverse;
        justify-content: space-between;
        padding: 10px 10px;
        height: 50px;
    }
    .header .more{
        display: flex;
        flex-direction: row-reverse;
        padding-left: 15px;
        font-size: small;
        font-weight: 600;
        justify-content: center;
        align-items: center;
        margin-top: 5px;
        color: rgb(176, 12, 141);
        cursor: pointer;
    }
    .more img{
        width: 15%;
    }
    .header .send {
        display: flex;
        flex-direction: row-reverse;
    }
    .header .send img{
        width: 20%;
    }
    .imgs{
        display: grid;
        grid-template-columns: repeat(6 , 160px);
        grid-template-rows: repeat(2, 125px);
        padding: 10px 20px;
    }
    .imgs img{
        width: 100px;
        height: 100px;
        cursor: pointer;

    }


</style>