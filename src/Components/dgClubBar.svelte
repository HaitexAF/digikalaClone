<script>
</script>
<div class="clubBar">
    <div class="digiClub">
        <img src="./pics/digiClub.svg" alt="">
    </div>
    <div class="items">
        <div class="item">
            <img class="pic" src="./pics/dcLuckyDraw.png" alt="">
            <h5>گردونه شانس</h5>
            <img class="icon" src="./pics/dcLucky.png" alt="">
        </div>
        <div class="item">
            <img class="pic" src="./pics/dcMissions.png" alt="">
            <h5>ماموریت ها</h5>
            <img class="icon" src="./pics/dcGoal.png" alt="">
        </div>
        <div class="item">
            <img class="pic" src="./pics/dcAwards.png" alt="">
            <h5>جایزه ها</h5>
            <img class="icon" src="./pics/dcGift.png" alt="">
        </div>
    </div>
</div>
<style>
    @font-face {
    font-family: myFirstFont;
    src:url('/Yekan.ttf');
    }
    .clubBar{
        background:linear-gradient(to left,rgb(25, 67, 112), rgb(90, 179, 242)) ;
        display: flex;
        flex-direction: row-reverse;
        justify-content: space-between;
        margin: 0% 10%;
        border-radius: 15px;
        font-family: myFirstFont;

    }
    .digiClub{
        display: flex;
        align-items: center;
        text-align: center;
        justify-content: center;
        margin: 0px 30px;

    }
    .items{
        display: flex;
        flex-direction: row-reverse;
        margin-left: 15px;
    }
    .item{
        display: flex;
        background: #fff;
        margin:10px 3px;
        align-items: center;
    }
    .item:nth-child(1){
        border-radius: 0px 10px 10px 0px;
    }
    .item:nth-child(3){
        border-radius: 10px 0px 0px 10px;
    }
    .item .pic{
        width: 150px;
        height: 60px;
    }
    .item:nth-child(3) .pic{
        border-radius: 10px 0px 0px 10px;
    }
    .item .icon{
        width: 10%;
        margin-left: 5px;
    }
</style>