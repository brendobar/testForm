<template>
    <div class="top">
        <form action="/search/" target="_blank" class="form-search">
            <input type="search" name="text" required placeholder="Поиск по сайту">
            <input type="submit" value="&#128269;">
        </form>
        <div class="profile">
            <img class="profileImg" src="@/static/profile.png" alt="">
            <div class="info">
                <p class="name">Alexander C.</p>
                <p class="role">Администратор</p>
            </div>
            
        </div>
        
    </div>
</template>

<style>
p{
    margin-block-start: .5em;
    margin-block-end: .5em;
    font-size: 1vw;
    text-align: center;
    color: black;
    font-family: Calibri;
}
.top{
    margin-left: auto;
    margin-right: 0;
    width: 93%;
}
.form-search {
    margin: 2% 20% 2% 10%;
    width: 40%;
    display: inline-block;
    border: .02em solid #00000030;
}
.form-search input {
    all: unset;
}
input[type="search"] {
    width: 95%;
}
.profile{
    position: absolute;
    right: 0;
    display: inline-flex;
    width: 30%;
}
.profileImg{
    position: relative;
    left: 0;
    width: 15%;
}
.info{
    position: relative;
    right: 0;
    width: 30%;
}
.name{
    font-size: 1.2vw;
    font-weight: bold;
}
.role{
    color: #00000070;
}

</style>