<template>
<div class="login">
    <div class="login-bgc">
        <div class="bgc"></div>
        <div class="bgc"></div>
        <div class="bgc"></div>
        <div class="bgc"></div>
        <div class="bgc"></div>
        <div class="bgc"></div>
    </div>
    <div class="container">
        <div class="login-header">
            <img class="icon icon-header" src="../../../assets/images/sort.png" alt="">
        </div>
        <div class="login-main">
            <div class="main-title flex-center">
                <div>
                    <div class="blod-text title-text">Mirroring Cast screen</div>
                    <div class="real-text mt-8">Real-time screen sharing</div>
                </div>
                <div class="clock">
                    <img class="icon-clock" src="../../../assets/images/clock.png" alt="">
                </div>
            </div>
            <div class="main-tv"></div>
        </div>
        <div class="login-footer">
            <div class="foot-crossing"></div>
            <div class="choosetextAll">
                <div class="blod-text choose-text">Please choose</div>
                <div class="flex-between">
                    <div class="scene-text">Choose a screencast scene</div>
                    <img class="icon" src="../../../assets/images/news.png" alt="">
                </div>
            </div>
            <div class="foot-header flex-center">
                <img class="icon icon-book mr-15" src="../../../assets/images/book.png" alt="">
                <div>
                    <div class="foot-text">Screen mirroring...</div>
                    <div class="foot-litle">Mobile screen sharing to TV</div>
                </div>
            </div>
            <div class="foot-header flex-center">
                <img class="icon icon-book mr-15" src="../../../assets/images/book.png" alt="">
                <div>
                    <div class="foot-text">Screen mirroring...</div>
                    <div class="foot-litle">Mobile screen sharing to TV</div>
                </div>
            </div>
        </div>
    </div>
</div>
</template>

<style>


/* .login{
    overflow: hidden;
} */
::-webkit-scrollbar {
    width: 0 !important
}
.login-bgc{
    display: grid;
    grid-template-columns: repeat(6,1fr);
    width: 100%;
    height: 100vh;
    position: fixed;
    z-index: -1;
}
.bgc{
    background: #7367fb;
}
.bgc:nth-of-type(odd){
    background: #7c71fe;
}
.login-header,.login-main{
    padding: 0 2.5rem;
}
.login-header{
    padding-top: 2.3rem;
}
.icon-header{
    margin:2rem 0;
}
.main-title{
    margin: 0 0 1.6rem 1rem;
}
.title-text,.choose-text{
    color: #fff;
    font-size: 1.8rem;
}
.real-text{
    color: #cecbf8;
    font-size: 1.4rem;
}
.clock{
    margin-left: 5.4rem;
    margin-top: 3.2rem;
}
.icon-clock{
    background: #9da3f9;
    border-radius: 3rem;
}
.main-tv{
    margin-left: 1.5rem;
    height: 22.3rem;
    background: url('../../../assets/images/people-tv.png')no-repeat;
}
.login-footer{
    /* height: 40.5rem; */
    background: linear-gradient(#6a69e1,#7d72fc,#7467fd);
    background: linear-gradient(to right,#8378fb,#9987eb);
    border-radius: 3rem;
    padding: 1.2rem 2.5rem 2.5rem 2.5rem;
}
.foot-crossing{
   background:  #c2c4f4;
    width: 4.4rem;
    height: 0.4rem;
    border-radius: 2rem;
    margin: 0 auto;
}
.choosetextAll{
    margin: 2.2rem 0;
}
.scene-text{
    font-size: 1.8rem;
    color: #c0c0f6;
}
.icon-book {
    background: #7b71f8;
    padding: 1.5rem;
    border-radius: 5rem;
}

.foot-header {
    padding: 3.7rem 2rem;
    background: #fff;
    border-radius: 3rem;
    margin-bottom: 1.9rem;
}
</style>