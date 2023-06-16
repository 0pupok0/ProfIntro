<template>
<div class="table">
    <h3>Оглавление</h3>
    <button @click="$emit('p1')" class="btns2">Определение экспертных систем</button>
    <button @click="$emit('p2')" class="btns2">История создания</button>
    <button @click="$emit('p3')" class="btns2">Современные экспертные системы</button>
    <button @click="$emit('p4')" class="btns2">Структура экспертной системы</button>
    <button @click="$emit('p5')" class="btns2">Эксперты и экспертные системы</button>
    <button @click="$emit('p6')" class="btns2">Искусственный интеллект и Экспертные системы</button>
    <button @click="$emit('p7')" class="btns2">Применение экспертных систем</button>
    <button @click="$emit('p8')" class="btns2" style="border:none">Заключение</button>
</div>
</template>
<script>
export default{
    name:"tableComp"
    
}
</script>
<style>
@font-face {
  font-family: "Alegreya";
  src: local("Alegreya"),
    url(../assets/AlegreyaSans-LightItalic.ttf)
    format("truetype");}
.table{
    font-family: "Alegreya";
    display:flex;
    flex-direction: column;
    border: 3px solid black;
    border-radius: 25px;
    background-color: white;
    width: 20vw;
    padding-bottom: 20px;
    margin: 20px;
    height:fit-content;
    position: sticky;
    top: 100px;
    text-align: center;
}
.btns2 {
    background: none;
    border:none;
    text-decoration: none;
    color: #000000;
    width: 100%;
    border-bottom: #cccccc 2px solid;
    text-align: center;
    font-size: 20px;
    font-family: "Alegreya";
}
.btns2:hover {
    background-color:  #f7d0d0;
}
</style>