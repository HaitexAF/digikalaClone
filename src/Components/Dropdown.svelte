<script>

</script>

<table>

    <div>
        <img src="./pics/more.png" alt="">
        <span>بیشتر</span>

    </div>
    <div>
        <img src="./pics/discount2.png" alt="">
        <span>حراج میان فصل</span>

    </div>
    <div>
        <img src="./pics/plus.png" alt="">
        <span>دیجی پلاس</span>

    </div>
    <div>
        <img src="./pics/mission.png" alt="">
        <span>ماموریت‌ها</span>

    </div>
    <div>
        <img src="./pics/mehr.png" alt="">
        <span>دیجی‌کالا مهر</span>

    </div>
    <div>
        <img src="./pics/digiP.png" alt="">
        <span>دیجی پی</span>

    </div>
    <div>
        <img src="./pics/ds.png" alt="">
        <span>دیجی استایل</span>

    </div>
    <div>
        <img src="./pics/jet.png" alt="">
        <span>دیجی‌کالا جت</span>

    </div>
</table>
<style>
    @font-face {
    font-family: myFirstFont;
    src:url('/Yekan.ttf');
    }

    table{
        display: grid;
        grid-template-columns: repeat(8 , 140px);
        justify-content: center;
        margin: 1% 10%;
        /* justify-content: space-between;
        flex-flow: wrap; */
        /* flex-wrap: wrap; */
        /* align-items: center; */
        /* justify-content: center space-between; */
        /* padding: 20px 70px; */
        /* width: 90%; */
    }
    div{
        display: grid;
        align-items: center;
        justify-content: center;
    }
    span{
        /* padding-left: 100px; */
        font-size: 13px;
        cursor: pointer;
        font-family: myFirstFont;   
        margin-top: 1%;
        text-align: center;
        /* width: 160px; */
    }
    img{
        display: flex;
        width: 50px;
        height: 50px;
        
    }
</style>