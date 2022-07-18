<template>
    <section id="section2">
            <article class="sec2_inner container">
                <div class="sec2_wrap">
                    <div class="sec2_title">
                        <span>award</span>
                        <h2>best<br/>musical</h2>
                        <p>한국 뮤지컬 최초<br/>그랜드슬램 달성</p>
                    </div>
                    <div class="news_top">
                        <div class="top_t">
                            <span>조선일보</span>
                            <p>압도적인 무대로 관객을 빨아들인다.<br/>5년 제작기간이 헛되지 않았음을<br/>증명하는 장업한 무대미술</p>
                        </div>
                        <div class="top_b">
                            <span>국민일보</span>
                            <p>베일벗은 '웃는 남자'<br/>미치도록 매혹적인<br/>그와 함께하는 황홀경</p>
                        </div>
                    </div>
                    <div class="news_bottom">
                        <div class="bottom_t">
                            <span>뉴시스</span>
                            <p>웰메이드 뮤지컬의 탄생!<br/>눈부셨고, 귀는 황홀했으며,<br/>마음은 어릿했다.</p>
                        </div>
                        <div class="bottom_b">
                            <span>국민일보</span>
                            <p>탄탄한 서사와 환상적인 무대,<br/>중독성 강한 음악까지<br/>한국 창작 뮤지컬사에 한 획을 그은 작품</p>
                        </div>
                    </div>
                </div>
            </article>
        </section>
</template>

<style scoped>
#section2 {
    padding: 100px 0;
    background: url(../assets/img/bg2.jpg);
    color: #fff;
}
.sec2_wrap {display: flex;}
.sec2_wrap .sec2_title {
    width: 33.3333%;
    padding: 20px;
}
.sec2_wrap .sec2_title span {
    background: #ff3344;
    padding: 3px 60px;
    border-radius: 50px;
    text-transform: uppercase;
    font-size: 14px;
    color: #fff;
}
.sec2_wrap .sec2_title h2 {
    padding: 15px 0;
    font-size: 50px;
    line-height: 50px;
    font-weight: bold;
    text-transform: uppercase;
}
.sec2_wrap .sec2_title p {
    padding: 15px 0;
    font-size: 18px;
    font-weight: bold;
}
.sec2_wrap .news_top {
    width: 33.3333%;
}
.sec2_wrap .news_top .top_t {
    padding: 20px;
}
.sec2_wrap .news_top .top_b {
    padding: 20px;
}
.sec2_wrap .news_top span {
    display: block;
    padding-bottom: 20px;
    font-size: 24px;
    font-weight: bold;
}
.sec2_wrap .news_top p {
    font-size: 18px;
}
.sec2_wrap .news_bottom {
    width: 33.3333%;
}
.sec2_wrap .news_bottom .bottom_t {
    padding: 20px;
}
.sec2_wrap .news_bottom .bottom_b {
    padding: 20px;
}
.sec2_wrap .news_bottom span {
    display: block;
    padding-bottom: 20px;
    font-size: 24px;
    font-weight: bold;
}
.sec2_wrap .news_bottom p {
    font-size: 18px;
}
</style>