<template>
        <section id="section1">
        <article class="sec1_wrap">
            <div class="slider">
                <div class="sec1_inner container">
                    <div class="desc">
                        <h2>2022 THE MAN WHO LAUGHS</h2>
                        <p>‘부자들의 낙원은 가난한 자들의 지옥으로 세워진 것이다’</p>
                        <a href="/">MORE</a>
                    </div>
                    <div class="bullet">
                        <span></span>
                        <span></span>
                        <span></span>
                        <span></span>
                    </div>
                    <div class="prev"><i class="fas fa-chevron-left"></i></div>
                    <div class="next"><i class="fas fa-chevron-right"></i></div>
                </div>
            </div>
        </article>
    </section>
</template>

<style scoped>
@charset "utf-8";

#section1 {}
.sec1_wrap {}
.sec1_wrap .sec1_inner {}
.sec1_wrap .slider {
    position: relative;
    width: 100%;
    height: 600px;
    background: url(../assets/img/slider_img.jpg) no-repeat center center;
}
.sec1_wrap .slider .desc {
    position: absolute;
    left: 40%;
    bottom: 50px;
    transform: translate(-50%);
    color: #fff;
}
.sec1_wrap .slider .desc h2 {
    padding-bottom: 20px;
    font-size: 60px;
}
.sec1_wrap .slider .desc p {
    font-size: 21px;
    padding-bottom: 50px;
}
.sec1_wrap .slider .desc a {
    padding: 10px 50px;
    background: #f6151b;
    color: #fff;
}
.sec1_wrap .slider .bullet{
    position: absolute;
    left: 50%;
    bottom: 20px;
    transform: translate(-50%);
}
.sec1_wrap .slider .bullet span {
    display: inline-block;
    width: 15px;
    height: 15px;
    margin: 0 5px;
    background: #fff;
    border-radius: 50%;
    cursor: pointer;
}
.sec1_wrap .slider .prev {
    position: absolute;
    top: 50%;
    left: 20px;
    color: #fff;
    font-size: 60px;
    transform: translate(0%, -50%);
    cursor: pointer;
}
.sec1_wrap .slider .next {
    position: absolute;
    top: 50%;
    right: 20px;
    color: #fff;
    font-size: 60px;
    transform: translate(0%, -50%);
    cursor: pointer;
}
</style>