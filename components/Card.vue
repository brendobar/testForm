<template>
    <div class="condition" id="c">
        <div class="and">И</div>
        <div class="typeCard" id="t1">
            <p>Условие 2</p>
            <select name="card" id="card" >
                <option value="" disabled selected>Выберете условие</option>
                <option value="Возраст респондента">Возраст респондента</option>
                <option value="Тип карты">Тип карты</option>
                <option value="Статус карты лояльности">Статус карты лояльности</option>
            </select>
        </div>
        <div class="typeCard" id="t2">
            <p>Тип 1</p>
            <select name="card" id="card">
                <option value="Standart" selected>Standart</option>
                <option value="Silver">Silver</option>
                <option value="Gold">Gold</option>
            </select>
        </div>
        
    </div>
</template>


<style>
.typeCard{
    width: 100%;
    position: absolute;
    display: inline-block;
}
.typeCard p{
    display: inline-block;
    font-weight: bold;
    color:darkcyan;
}
select#card{
    position: absolute;
    right: 5%;
    width: 65%;
    height: 100%;
    border-color: #00000020;
}
#t1{
    margin-top: 3%;
}
#t2{
    position: absolute;
    margin-top: 8%;
    color: black;
    font-weight: normal;
}
#t2 p{
    color: black;
    font-weight: normal;
}
#c{
    margin-top: 5%;
}
.and{
    width: 1%;
    padding: 0.5%;
    border-radius: 15%;
    font-weight: normal;
    font-family: Calibri;
    background-color: #008b8b50;
    display: inline-block;
    position: absolute;
}
</style>