<template>
import React from 'react'

function Footer() {
  return (
    <footer id="footer">
        <h2 class="ir_so">푸터 영역</h2>
        <div class="footer__inner container">
            <div class="footer__menu">
                <div class="sns_wrap">
                    <h2>emk</h2>
                    <p>sns를 통해<br/>더 많은 정보를 확인!</p>
                    <ul class="sns">
                        <li><a href="/"><i class="fab fa-instagram"></i><span class="ir_so">인스타</span></a></li>
                        <li><a href="/"><i class="fab fa-facebook-square"></i><span class="ir_so">페이스북</span></a></li>
                        <li><a href="/"><i class="fab fa-twitter"></i><span class="ir_so">트위터</span></a></li>
                        <li><a href="/"><i class="fab fa-youtube"></i><span class="ir_so">유튜브</span></a></li>
                    </ul>
                </div>
                <div>
                    <h3>사이트</h3>
                    <ul>
                        <li><a href="/">레이아웃 유형01</a></li>
                        <li><a href="/">레이아웃 유형02</a></li>
                        <li><a href="/">레이아웃 유형03</a></li>
                        <li><a href="/">레이아웃 유형04</a></li>
                    </ul>
                </div>
                <div>
                    <h3>사이트</h3>
                    <ul>
                        <li><a href="/">레이아웃 유형01</a></li>
                        <li><a href="/">레이아웃 유형02</a></li>
                        <li><a href="/">레이아웃 유형03</a></li>
                        <li><a href="/">레이아웃 유형04</a></li>
                    </ul>
                </div>
                <div>
                    <h3>사이트</h3>
                    <ul>
                        <li><a href="/">레이아웃 유형01</a></li>
                        <li><a href="/">레이아웃 유형02</a></li>
                        <li><a href="/">레이아웃 유형03</a></li>
                        <li><a href="/">레이아웃 유형04</a></li>
                    </ul>
                </div>
                <div>
                    <h3>사이트</h3>
                    <ul>
                        <li><a href="/">레이아웃 유형01</a></li>
                        <li><a href="/">레이아웃 유형02</a></li>
                        <li><a href="/">레이아웃 유형03</a></li>
                        <li><a href="/">레이아웃 유형04</a></li>
                    </ul>
                </div>
            </div>
            <address class="footer__right">
                ©2022 KwonYongBin. All rights reserved.
            </address>
        </div>
    </footer>
  )
}

export default Footer
</template>

<style scoped>
.footer__menu {
  display: flex;
  justify-content: space-between;
}
.footer__menu > div {
  width: 16%;
  text-align: left;
}
.footer__menu .sns_wrap {
  width: 36%;
}
.footer__menu .sns_wrap h2 {
  padding-bottom: 20px;
  font-size: 28px;
  font-weight: bold;
  text-transform: uppercase;
}
.footer__menu .sns_wrap p {
  padding-bottom: 20px;
  text-transform: uppercase;
}
.sns li {
  display: inline-block;
  padding: 0 15px;
}
.sns li:first-child {padding-left: 0;}
.sns li:last-child {padding-right: 0;}
.sns li a i{font-size: 30px;}
.footer__menu > div h3 {
  font-size: 22px;
  font-weight: 500;
  margin-bottom: 20px;
}
.footer__menu > div li a {
  font-size: 16px;
  line-height: 1.6;
  color: #777;
  font-weight: 300;
}
.footer__right {
  border-top: 1px solid #ccc;
  margin-top: 50px;
  padding-top: 50px;
  text-align: center;
}
</style>