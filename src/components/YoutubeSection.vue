<template>
    <section id="section5">
        <article class="sec5_inner container">
            <div class="yt">
                <h2>웃는 남자 유튜브</h2>
                <p>웃는 남자 배우들의 무대인사 커튼 콜</p>
                <a href="/">바로가기</a>
            </div>
        </article>
    </section>
</template>

<style scoped>
.yt {
    position: relative;
    padding: 130px 0;
}
.yt::before {
    content: '';
    width: 641px;
    height: 287px;
    background: url(../assets/img/yt.png) no-repeat center center;
    position: absolute;
    right: 0;
    top: 50%;
    transform: translate(0,-50%);
}
.yt h2 {
    font-size: 50px;
    padding-bottom: 40px;
}
.yt p {
    font-size: 24px;
    padding-bottom: 70px;
}
.yt a {
    display: inline-block;
    font-size: 18px;
    background: #ff4433;
    padding: 15px 30px;
    color: #fff;
}
</style>