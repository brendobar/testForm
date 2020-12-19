<template>
    <div class="addBlock">
        <p class="name">Добавить опрос</p>
        <form action="" class="poll">
			<Age/>
			<div class="btnBlock" id="b1">
                <button class="plus">Добавить диапазон</button>
                <button class="del">Удалить условие</button>
            </div>
			<Card/>
			<div class="btnBlock" id="b2">
                <button class="plus">Добавить диапазон</button>
                <button class="del">Удалить условие</button>
            </div>
			<Status/>
			<div class="btnBlock" id="b3">
                <button class="plus">Добавить диапазон</button>
                <button class="del">Удалить условие</button>
            </div>
			<div class="finBtnBlock">
				<button class="testPoll">Протестировать опрос</button>
				<input type="submit" class="Next" value="Далее">
			</div>
			
        </form>
        
    </div>

</template>


<script>

import Age from "@/components/Age"
import Card from "@/components/Card"
import Status from "@/components/Status"

export default {
    components: {
		Age,
		Card,
		Status
  }
}

</script>





<style>

.addBlock{
    width: 87%;
    display: block;
    position: absolute;
    margin-top: 6%;
    margin-left: 5%;
}
.name{
    width: 10vw;
    margin-block-start: .5em;
    margin-block-end: .5em;
    font-size: 1vw;
    text-align: center;
    color: #00000070;
    font-weight: normal;
    font-family: Calibri;
}
.btnBlock{
    width: 70%;
    position: absolute;
    right: 0;
	

}
.btnBlock button{
    padding: 1%;
    width: 20%;
    border-radius: 5%;
}
.plus{
    border: 1px solid greenyellow;
}
.del{
    position: absolute;
    right: 10%;
    border: 1px solid red;
}
#b2, #b3{
	margin-top: 12%;
}
.finBtnBlock{
	width: 95%;
    position: absolute;
    bottom: -100%;
	padding-bottom: 7%;
}
.testPoll{
	border: 1px solid #00000020;
	color:darkseagreen;
	font-weight: bold;
	padding: 1%;
    width: 20%;
}
.Next{
	border: 0px solid;
	color:white;
	font-weight: bold;
	background-color: darkseagreen;
	padding: 1%;
    width: 20%;
	position: absolute;
	right: 0;
}

</style>