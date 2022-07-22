<script>
</script>
<main>
    <div class="header">
        <div class="leftObjects">
            <img src="./pics/basketIcon.png" alt="basketIcon">
            <h2> | </h2>
            <button>Sign Up | Sign In</button>
        </div>
        <div class="rightObjects">
            <img src="./pics/search.png" alt="">
            <input type="text" placeholder="Search" >
            <h2>
                <a href="https:/digikala.com" target="_blank" >digikala</a> 
            </h2>
        </div>
    </div>
</main>
<style>
    @import url('https://fonts.googleapis.com/css2?family=Secular+One&display=swap');
    .header{
        display: flex;
        justify-content: space-between;
        width: 100vw;
    }
    /* .header > div{
        position: relative;
        bottom: 10px;
    } */
    .leftObjects{
        display: flex;
    }
    .leftObjects img{
        width: 50px;
        height: 55px;
        /* height: 100px; */
        /* border-right: 1px solid lightgrey; */
        /* margin-right: 10px; */
        /* margin-top: 10px; */
        padding: 10px 10px;
        cursor: pointer;
        position: relative;
        bottom: 5px;
    }
    .leftObjects h2{
        margin-top: 8px;
        color: lightgray;
        /* width: 4px; */
        font-weight: 100;
        
    }
    button{
        /* display: grid; */
        background: #fff;
        font-weight: 500;
        width: 120px;
        height: 30px;
        margin-top: 10px;
        margin-left: 10px;
        text-align: center;
        justify-content: center;
        align-items: center;
        position: relative;
        /* bottom:28px; */
        border: 1px solid lightgrey;
        border-radius: 5px;
        cursor: pointer;
        /* border-left: 1px solid red; */
    }
    .rightObjects{
        display: flex;
        flex-direction: row;
        padding: 10px 10px;
        /* position: relative; */
    }
    .rightObjects img{
        width: 22px;
        height: 22px;
        position: relative;
        left: 30px;
        top: 6px;
        cursor: pointer;

    }
    input{
        background: hsl(0, 0%, 94%);
        border: none;
        border-radius: 5px;
        padding-left: 35px;
        height: 35px;
        width: 450px;
        margin-right: 10px;
    }
    .rightObjects h2 a{
        font-size: 30px;
        font-weight: bold;
        color: red;
        cursor: pointer;
        font-family: 'Secular One', sans-serif;
        position: relative;
        /* bottom: 0px; */
        text-decoration: none;
        
    }
</style>