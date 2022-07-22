<script>

</script>
<main>
    <div class="box">
        <div class="text">
            <h2>محبوب‌ترین برندها</h2>
            <img src="./pics/star.png" alt="">

        </div>
        <div class="items">
            <div class="item">
                <img src="./pics/ppBijan.png" alt="">
            </div>
            <div class="item">
                <img class="mi" src="./pics/ppMi.png" alt="">
            </div>
            <div class="item">
                <img class="sp" src="./pics/ppSP.png" alt="">
            </div>
            <div class="item">
                <img src="./pics/ppTsco.png" alt="">
            </div>
            <div class="item">
                <img src="./pics/ppKale.png" alt="">
            </div>
            <div class="item">
                <img src="./pics/ppKingStar.png" alt="">
            </div>
            <div class="item">
                <img src="./pics/ppPercil.png" alt="">
            </div>
            <div class="item">
                <img src="./pics/ppPril.png" alt="">
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
        display: grid;
        justify-content: center;
        text-align: center;
        align-items: center;
        margin-top: 25px;
        border-radius: 15px;
        border: 1px solid rgba(0, 0, 0, 0.358);
        background: rgba(211, 211, 211, 0.106);
        width: 1200px;
        height: 200px;
        position: relative;
        left: 200px;
    }
    .text{
        display: flex;
        font-family: myFirstFont;
        font-size: 18px;
        margin-top: 15px;
        text-align: center;
        justify-content: center;
    }
    .text img{
        width: 30px;
        height: 30px;
        position: relative;
        top: 6px;
        left: 5px;
    }
    .items{
        display: flex;
    }
    .item .sp{
        width: 100px;
        height: 50px;
        position: relative;
        top: 30px;
        right: 15px;
    }
    .item .mi{
        width: 100px;
        height: 50px;
        position: relative;
        top: 30px;
    }
    .item img{
        width: 120px;
        height: 120px;
        margin-left: 30px;
        cursor: pointer;
    }


</style>