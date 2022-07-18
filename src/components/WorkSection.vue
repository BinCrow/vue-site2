<template>
        <section id="section4">
        <article class="sec4_inner container">
            <div class="sec4_title">
                <h2>다른작품 구경하기</h2>
                <p>emk가 선사하는 다양한 뮤지컬</p>
            </div>
            <ul class="sec4_top">
                <li>
                    <div class="sec4_img"></div>
                    <strong>웃는남자</strong>
                    <p>2022 THE MAN WHO LAUGHS</p>
                    <a href="/">more</a>
                </li>
                <li>
                    <div class="sec4_img"></div>
                    <strong>마타하리</strong>
                    <p>2022 MATA HARI</p>
                    <a href="/">more</a>
                </li>
                <li>
                    <div class="sec4_img"></div>
                    <strong>레베카</strong>
                    <p>2022 REBECCA</p>
                    <a href="/">more</a>
                </li>
                <li>
                    <div class="sec4_img"></div>
                    <strong>팬텀</strong>
                    <p>2022 PHANTOM</p>
                    <a href="/">more</a>
                </li>
            </ul>
            <ul class="sec4_bottom">
                <li>
                    <div class="sec4_img"></div>
                    <strong>몬테크리스토</strong>
                    <p>2022 MONTE CRISTO</p>
                    <a href="/">more</a>
                </li>
                <li>
                    <div class="sec4_img"></div>
                    <strong>모차르트</strong>
                    <p>2022 MOZART!</p>
                    <a href="/">more</a>
                </li>
                <li>
                    <div class="sec4_img"></div>
                    <strong>엑스칼리버</strong>
                    <p>2022 XCALIBUR</p>
                    <a href="/">more</a>
                </li>
                <li>
                    <div class="sec4_img"></div>
                    <strong>프리다</strong>
                    <p>2022 FRIDA</p>
                    <a href="/">more</a>
                </li>
            </ul>
        </article>
    </section>
</template>

<style scoped>

#section4 {
    padding: 100px 0;
    background: url(../assets/img/bg1.jpg) no-repeat center center;
    background-size: cover;
    color: #fff;
}
.sec4_title {
    text-align: center;
}
.sec4_title h2 {
    padding: 50px 0 10px 0;
    font-size: 50px;
    color: #fff;
}
.sec4_title p {
    text-transform: uppercase;
    padding: 50px;
    font-size: 21px;
}
.sec4_inner ul {
    padding: 30px 0;
}
.sec4_inner .sec4_top {
    display: flex;
    justify-content: space-between;
}
.sec4_top li {
    text-align: center;
}
.sec4_top li .sec4_img {
    width: 265px;
    height: 380px;
}
.sec4_top li:nth-child(1) .sec4_img {
    background: url(../assets/img/mu1.jpg) no-repeat center center;
    background-size: cover;
}
.sec4_top li:nth-child(2) .sec4_img {
    background: url(../assets/img/mu2.jpg) no-repeat center center;
    background-size: cover;
}
.sec4_top li:nth-child(3) .sec4_img {
    background: url(../assets/img/mu5.jpg) no-repeat center center;
    background-size: cover;
}
.sec4_top li:nth-child(4) .sec4_img {
    background: url(../assets/img/mu6.jpg) no-repeat center center;
    background-size: cover;
}
.sec4_top li strong {
    display: block;
    padding: 20px 0;
    font-size: 28px;
}
.sec4_top li p {
    padding-bottom: 20px;
    font-size: 18px;
}
.sec4_top li a {
    display: block;
    padding: 15px 30px;
    background: #ff3344;
    font-size: 21px;
    color: #fff;
    text-transform: uppercase;
}
.sec4_inner .sec4_bottom {
    display: flex;
    justify-content: space-between;
}
.sec4_bottom li {
    text-align: center;
}
.sec4_bottom li .sec4_img {
    width: 275px;
    height: 380px;
}
.sec4_bottom li:nth-child(1) .sec4_img {
    background: url(../assets/img/mu8.jpg) no-repeat center center;
    background-size: cover;
}
.sec4_bottom li:nth-child(2) .sec4_img {
    background: url(../assets/img/mu7.jpg) no-repeat center center;
    background-size: cover;
}
.sec4_bottom li:nth-child(3) .sec4_img {
    background: url(../assets/img/mu4.jpg) no-repeat center center;
    background-size: cover;
}
.sec4_bottom li:nth-child(4) .sec4_img {
    background: url(../assets/img/mu3.jpg) no-repeat center center;
    background-size: cover;
}
.sec4_bottom li strong {
    display: block;
    padding: 20px 0;
    font-size: 28px;
}
.sec4_bottom li p {
    padding-bottom: 20px;
    font-size: 18px;
}
.sec4_bottom li a {
    display: block;
    padding: 15px 30px;
    background: #ff3344;
    font-size: 21px;
    color: #fff;
    text-transform: uppercase;
}
</style>