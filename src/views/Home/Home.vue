<template>
    <div class="home">
        <div class="header">
            <div class="nav flex-center">
                <img class="icon mr-52" src="../../assets/images/leftArrow.png" alt="">
                <div class="title">Local screencast</div>
            </div>
            <div>
                <input class="header-ipt" type="text" placeholder="search">
            </div>
        </div>
        <div class="main">
            <div class="main-ipt">
                <img class="main-waaw" src="../../assets/images/waaw.png" alt="">
                <div class="main-text">Mirror guide</div>
                <div class="main-litletext">common problem</div>
            </div>
            <div class="main-module flex-center">
                <div class="main-img">
                    <img class="icon main-icon" src="../../assets/images/pic.png" alt="">
                    <div class="icon-text">Picture</div>
                    <div class="icon-litle">Local screencast</div>
                </div>
                <div class="main-file">
                    <img class="icon file-icon" src="../../assets/images/folder.png" alt="">
                    <div class="file-text">file</div>
                    <div class="icon-litle">Local document</div>
                </div>
                <div class="main-file">
                    <img class="icon file-icon" src="../../assets/images/folder.png" alt="">
                    <div class="file-text">file</div>
                    <div class="icon-litle">Local document</div>
                </div>
            </div>
        </div>
        <div class="footer">
            <div class="footer-main">
                <div class="foot-header flex-center">
                    <img class="icon icon-book mr-15" src="../../assets/images/book.png" alt="">
                    <div>
                        <div class="foot-text">Screen mirroring...</div>
                        <div class="foot-litle">Mobile screen sharing to TV</div>
                    </div>
                </div>
            </div>
            <div class="footer-btn">
                <div class="flex-center">
                    <div class="btn-time flex-content mr-20">
                        <img class="icon" src="../../assets/images/suspend.png" alt="">
                        <div>Time out</div>
                    </div>
                    <div class="btn-off flex-content">
                        <img class="icon" src="../../assets/images/off.png" alt="">
                        <div>End</div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>


<style scoped>


.icon-text,.file-text,.foot-text,.icon-litle,.foot-litle{
    /* 文本超出省略 */
        text-overflow: ellipsis;
        /* 写的时候不换行 */
        white-space: nowrap;
}
.home{
    padding: 2rem 2.3rem;
    background: linear-gradient(#dbcbf7,#ebeff7);
    border-radius: 3rem;
}
.main{
    padding-top:2rem;
}
.nav{
    margin: 2rem 0;
}
.title{
    font-size: 2rem;
    font-weight: bold;
}
.header-ipt{
    width: 32rem;
    padding: 2rem 0;
    font-size: 2.4rem;
    border-radius: 2rem;
    background: url('../../assets/images/search.png') no-repeat 90% center;
    background-size: 2.4rem;
    text-indent: 2rem;
    border: none;
    background-color: #ffffff;
}
.main-ipt{
    width: 33rem;
    height: 12rem;
    background-size: 10rem;
    margin:2rem 0;
    border-radius: 5rem;
    background-color: #eceaff;
}
.main-waaw{
    width: 11rem;
    position: absolute;
    top: 18rem;
    left: 4rem;
}
.main-text{
    padding-top: 3rem;
    font-size: 2.4rem;
    font-weight: bold;
}
.main-litletext{
    font-size: 1.7rem;
    color: #5d6a7d;
}
.main-text,.main-litletext{
    padding-left:13.2rem ;
}
.main-module{
    margin-top: 3.5rem;
    height: 17.4rem;
    overflow-x: scroll;
    gap: 0 15px;
}
.main-img,.main-file{
    padding: 3rem 1rem;
    border-radius: 2rem;
}
.main-img{
    background-color: #7468fc;
}
.main-file{
    background-color: #ffffff;
}
.main-icon,.file-icon{
    padding: 1.5rem;
    border-radius: 1.5rem;
    margin-left: 3rem;
}
.main-icon{
    background: rgb(210, 213, 254);
}
.file-icon{
    background: #fdeadc;
}
.icon-text,.file-text{
    text-align: center;
}
.icon-text,.file-text,.foot-text{
    font-size: 2rem;
    font-weight: bold; 
}
.icon-text{
    color: #fff;
}
.icon-litle,.foot-litle{
   font-size: 1.5rem;
   color: #a8a3f7;
}
.footer{
    margin-top: 3.5rem;
    border-radius: 4rem;
    background: #e5e2ff;
    padding-bottom: 3.5rem;
}
.footer-main{
    background: #fff;
    border-radius: 3rem;
    padding: 3.7rem 2rem;
}
.icon-book{
    background: #7b71f8;
    padding: 1.5rem;
    border-radius: 5rem ;
}

.footer-btn{
    margin:4rem 2rem 0 2rem;
}
.btn-time,.btn-off{
    width: 14rem;
    height: 5rem;
    border-radius: 3rem;
    background: #fff;
    font-size: 1.5rem;
    font-weight: bold;
}
</style>