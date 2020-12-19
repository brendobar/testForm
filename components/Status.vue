<template>
    <div class="condition" id="s">
        <div class="and" id="and_g">И</div>
        <div class="status" id="s1">
            <p>Условие 3</p>
            <select name="card" id="status" >
                <option value="" disabled selected>Выберете условие</option>
                <option value="Возраст респондента">Возраст респондента</option>
                <option value="Тип карты">Тип карты</option>
                <option value="Статус карты лояльности">Статус карты лояльности</option>
            </select>
        </div>
        <div class="status" id="s2">
            <p>Тип 1</p>
            <select name="card" id="card">
                <option value="Активна" selected>Активна</option>
                <option value="Не активна">Не активна</option>
            </select>
        </div>
        
    </div>
</template>



<style>
.status{
    width: 100%;
    position: absolute;
    display: inline-block;
}
.status p{
    display: inline-block;
    font-weight: bold;
    color:#d0f5ab;
}
select#status{
    position: absolute;
    right: 5%;
    width: 65%;
    height: 100%;
    border-color: #00000020;
}
#s1{
    margin-top: 3%;
}
#s2{
    position: absolute;
    margin-top: 8%;
    color: black;
    font-weight: normal;
}
#s2 p{
    color: black;
    font-weight: normal;
}
#s{
    margin-top: 20%;
}
.and{
    width: 1%;
    padding: 0.5%;
    border-radius: 15%;
    font-weight: normal;
    font-family: Calibri;
    display: inline-block;
    position: absolute;
}
#and_g{
    background-color: #d0f5ab50;
}
</style>