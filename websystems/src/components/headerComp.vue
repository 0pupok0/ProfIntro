<template>
<div class="header">
    Применениие экспертных систем в информационных системах
</div>
</template>
<script>
export default{
    name:"headerComp"
}
</script>
<style>
@font-face {
  font-family: "Alegreya";
  src: local("Alegreya"),
    url(../assets/AlegreyaSans-LightItalic.ttf)
    format("truetype");}
.header{
    font-family: "Alegreya";
    font-size: 22px;
    background: #2e2e3a;
    height: 3vw;
    min-height: 30px;
    color: white;
    text-align: center;
    display:flex;
    justify-content: center;
    align-content: center;
    vertical-align: middle;
    line-height: 3vw;
    padding: 5px;
    position: fixed;
    width:100vw;
}
</style>