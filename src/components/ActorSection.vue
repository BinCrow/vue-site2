<template>
    <section id="section3">
        <article class="sec3_inner container">
            <h2>웃는 남자 출연배우</h2>
            <div class="actor_wrap">
                <div class="actor1">
                    <div class="img1"></div>
                    <div class="text">
                        <strong>박효신</strong>
                        <a href="/">자세히보기</a>
                    </div>
                </div>
                <div class="actor2">
                    <div class="img2"></div>
                    <div class="text">
                        <strong>박은태</strong>
                        <a href="/">자세히보기</a>
                    </div>
                </div>
                <div class="actor3">
                    <div class="img3"></div>
                    <div class="text">
                        <strong>박강현</strong>
                        <a href="/">자세히보기</a>
                    </div>
                </div>
            </div>
            <div class="more"><a href="/">배우 더 보기</a></div>
        </article>
    </section>
</template>

<style scoped>
#section3 {
    padding: 100px 0;
}
#section3 h2 {
    padding: 50px 0;
    font-size: 50px;
}
.sec3_inner {text-align: center;}
.actor_wrap {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-bottom: 50px;
}
.sec3_inner .more {
    display: inline-block;
    padding: 10px 50px;
    background: #ff3344;
    border-radius: 50px;
}
.sec3_inner .more a {
    font-size: 21px;
    color: #fff;
}
.actor_wrap>div {
    position: relative;
}
.actor_wrap .img1 {
    width: 370px;
    height: 520px;
    color: #fff;
}
.actor_wrap .img2 {
    width: 370px;
    height: 520px;
    color: #fff;
}
.actor_wrap .img3 {
    width: 370px;
    height: 520px;
    color: #fff;
}
.actor_wrap div .img1 {
    background: url(../assets/img/sec3_img01.jpg) no-repeat center center;
    background-size: cover;
}
.actor_wrap div .img2 {
    background: url(../assets/img/sec3_img03.jpg) no-repeat center center;
    background-size: cover;
}
.actor_wrap div .img3 {
    background: url(../assets/img/sec3_img02.jpg) no-repeat center center;
    background-size: cover;
}
.actor_wrap>div .text{
    position: absolute;
    left: 50%;
    bottom: 30px;
    transform: translate(-50%);
}
.actor_wrap strong {
    display: block;
    margin-bottom: 15px;
    font-size: 30px;
    color: #fff;
}
.actor_wrap a {
    font-size: 18px;
    display: block;
    color: #fff;
}
</style>