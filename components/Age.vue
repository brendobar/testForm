<template>
    <div class="condition" id="a">
                <div class="age">
                    <p>Условие 1</p>
                        <select name="age" id="age">
                            <option value="" disabled selected>Выберете условие</option>
                            <option value="Возраст респондента">Возраст респондента</option>
                            <option value="Тип карты">Тип карты</option>
                            <option value="Статус карты лояльности">Статус карты лояльности</option>
                        </select>
                </div>
                <div class="range">
                        <p>Диапазон 1</p>
                        <div class="input">
                            <input type="text" placeholder="от">
                            <input type="text" placeholder="до">
                        </div>
                        
                </div>
                <div class="or">ИЛИ</div>
                <div class="range" id="r2">
                        <p>Диапазон 1</p>
                        <div class="input">
                            <input type="text" placeholder="от">
                            <input type="text" placeholder="до">
                        </div>
                        
                </div>

            </div>
</template>






<style>
.age{
    width: 100%;
    position: absolute;
    display: inline-block;
}
.age p{
    display: inline-block;
    font-weight: bold;
    color:darkorange;
}
select#age{
    position: absolute;
    right: 5%;
    width: 65%;
    height: 100%;
    border-color: #00000020;
}
.range{
    margin-top: 5%;
    width: 95%;
    display: inline-block;
}
.range p{
    display: inline-block;
}
.input{
    display: inline-block;
    position: absolute;
    right: 48.5%;
}
.or{
    width: 2%;
    padding: 0.5%;
    border-radius: 15%;
    font-weight: normal;
    font-family: Calibri;
    background-color: #ff8c0050;
    position: absolute;
}
#r2{
    margin: 0;
    margin-left: 5%;
}

</style>