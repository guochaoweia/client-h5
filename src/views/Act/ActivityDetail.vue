<template>
    <div class="act-container">
        <div class="act-header flex-center">
            <img class="icon" src="../../assets/images/leftArrow.png" alt="">
            <div class="act-title blod-text">Mirror</div>
        </div>
        <div class="act-main">
            <div class="main-panel">
                <div class="blod-text panel-text">Strong connection ability</div>
                <div class=" panel-litle">Cloud projection</div>
                <img class="icon-panel" src="../../assets/images/panel.png" alt="">
            </div>
        </div>
        <div class="act-footer">
            <div class="foot-header">
                <div class="remain-text blod-text flex-content">Remaining time</div>
                <div class="time-text flex-content mt-10">
                    <div class="time-number">6</div>
                    <div class="time-number ml-5">6</div>
                    <div class="time-number ml-5">9</div>
                    <div class="ml-5">hour</div>
                    <div class="time-number ml-5">3</div>
                    <div class="time-number ml-5">8</div>
                    <div class="ml-5">minute</div>
                </div>
            </div>
            <div class="foot-main">
                <div class="time-bar flex-between">
                    <div>200 minutes in total</div>
                    <div>46min</div>
                </div>
                <div class="flex-content mt-12">
                    <div class="blue-bar"></div>
                    <div class="grey-bar"></div>
                </div>
                <div class="time-bar flex-between mt-40">
                    <div>365 minutes in total</div>
                    <div>46min</div>
                </div>
                <div class="flex-content mt-12">
                    <div class="blue-bar"></div>
                    <div class="grey-bar"></div>
                </div>
                <div class="time-bar flex-between mt-40">
                    <div>200 minutes in total</div>
                    <div>46min</div>
                </div>
                <div class="flex-content mt-12">
                    <div class="blue-bar"></div>
                    <div class="grey-bar"></div>
                </div>
            </div>
        </div>
    </div>
</template>

<style scoped>
.act-container{
    background: linear-gradient(#d0d3fe,#d8dff9);
    padding-top: 2.3rem;
}
.act-header,.act-main{
    margin: 0 2.3rem;
}
.act-header{
    padding: 2rem 0;
}
.act-title{
    margin: 0 auto;
    font-size: 2rem;
}
.main-panel{
    border-radius: 3rem;
    background: #7367fb;
    padding: 3.2rem 0 0 2.7rem;
    height: 26rem;
    margin-bottom: 4rem;
}
.panel-text{
    font-size: 2rem;
    color: #fff;
}
.panel-litle{
    font-size: 1.5rem;
    color: #dad1fc;
}
.icon-panel{
    position: absolute;
    bottom:26rem;
    left: 6rem;
}
.act-footer{
    border-radius: 3rem;
    background: #fff;
    padding: 2.3rem;
}
.foot-header{
    border-radius: 3rem 3rem 0 0;
    background: #e5e2ff;
    padding: 2.2rem 0;
}
.remain-text{
    font-size: 1.4rem;
    /* margin: 0 auto; */
}
.time-text{
    font-size: 1rem;
}
.time-number{
    padding: 0.5rem;
    background: #7169fd;
    color: #fff;
}
.foot-main{
    margin: 2.9rem 0;
}
.time-bar{
    font-size: 1.2rem;
}
.blue-bar{
    background: #7169fd;
    width: 20rem;
    border-radius:2rem ;
    height: 0.5rem;
}
.grey-bar{
    background: #eff2fb;
    height: 0.5rem;
    border-radius: 2rem;
    width: 12rem;
}
</style>