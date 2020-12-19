<template>
    <div class="workPlace">
        <div class="path">
            <img id="home" src="@/static/home.png" alt="">&#8594;<a href="" id="type">Опросы</a>&#8594;<a href="" id="action">Добавить опрос</a>
        </div>
        <div class="nav">
            <nav class="type">
                <a href="#">Параметры</a>
                <a href="#">Вопросы</a>
                <a href="#">Логика</a>
                <a href="#">Условия</a>
                <a href="#">Респонденты</a>
            </nav>	
        </div>
        <addPoll/>
    </div>
</template>

<script>

import addPoll from "@/components/addPoll"
export default {
    components: {
        addPoll
  }
    
}
</script>

<style>
.workPlace{
    margin-left: auto;
    margin-right: 0;
    width: 93%;
}
.path{
    position: absolute;
    right: 0;
    display: inline-block;
    width: 90%;
}
#home{
    width: 1.3vw;
}
.path a{
    display: inline-block;
    margin: 0 0.5vw;
    text-decoration: none;
    font-family: Calibri;
    color: black;
}
.type {
    margin: 3% auto 0 5%;
    display: table; 
    position: absolute;
    width: 83%; 
    height: 40px;
    border-bottom: 1px solid rgb(208, 245, 171);
}
.type a {
    text-decoration: none;
    display: table-cell;
    vertical-align: middle;
    min-width: 100px;
    font-size: 1.3vw;
    text-align: center;
    color: darkseagreen;
    font-family: Calibri;
    font-weight: bold;
}
.type a:hover {
    border-bottom: 5px solid rgb(208, 245, 171);
    color: black;
}
</style>

