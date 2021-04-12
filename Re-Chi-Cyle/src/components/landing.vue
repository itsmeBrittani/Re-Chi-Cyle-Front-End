<template>
  <h1>{{ msg }}</h1>
    <h2> Fast Facts about Recycling in Chicago </h2>
    <ul>
        <li>Less than 9% of Chicago's waste is recycled - the national average hovers roughly around 32% according to the EPA</li>
        <li>The rate of recycling decreased after Mayor Emanuel's introduction of the Blue Cart Program</li>
        <li>Conflicts of interest with landfill-owning, private recycling haulers have been an ongoing issue contributing to the declining rate </li>
    </ul>
    <h2>Re.Chi.Cyle was made in an effort to:</h2>
    <div class='landing-module-container'>
        <div class='landing-mod' id='find'><h3>Help residents find where to recycle certain materials</h3></div>
        <div class='landing-mod' id='learn'><h3>Educate residents on what and how to recycle</h3></div>
        <div class='landing-mod' id='action'><h3>Encourage residents to take part in influencing the structure and efficiency of recycling in the city</h3></div>
    </div>
</template>

<script setup>
import { defineProps } from 'vue'

defineProps({
  msg: String
})

</script>

<style scoped>
a {
  color: #42b983;
}

ul{
    width: 80%;
    text-align: center;
    margin: 0 auto;
    font-size: 14px;
    list-style-type: square;
}

.landing-module-container{
    display: flex;
    text-align: center;
    width: 90%;
    margin: 0 auto;
}

.landing-mod{
    width: 33%;
    height: 100px;
    margin: 0px 5px 10px 5px;
}

#find {
    border: 5px solid #077707;
}

#learn{
    border: 5px solid #F6BA13;
}

#action {
    border: 5px solid #6A040F;
}


</style>