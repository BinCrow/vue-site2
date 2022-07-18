<template>
    <header id="header" className="header gmarket">
        <h1><a href="/">emk</a></h1>
        <ul>
            <li><a href="/">메뉴1</a></li>
            <li><a href="/">메뉴2</a></li>
            <li><a href="/">메뉴3</a></li>
            <li><a href="/">메뉴4</a></li>
            <li><a href="/">메뉴5</a></li>
        </ul>
    </header>
</template>

<style scoped>
#header {
    width: 100%;
    height: 120px;
    background: #f6f8fd;
    text-align: center;
}
#header h1 {
    padding: 15px 0;
    text-transform: uppercase;
}
#header h1 a {
    font-size: 35px;
    color: red;
}
#header li {
    display: inline-block;
    padding: 0 50px;
}
#header li a {
    font-weight: bold;
}
</style>