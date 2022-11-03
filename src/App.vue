<template>
  <div id="app">
    <router-view/>
  </div>
</template>

<style>
@import url('https://fonts.googleapis.com/css2?family=Cinzel+Decorative&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Raleway:ital@1&display=swap');

:root{
  --primaryColor: #080344;
  --whitecolor: #ffffff;
  --paragraphColor: #727272;
}

body{
  font-family: 'Raleway';
  font-size: 16px;
  overflow-x: hidden;
}

h1,h2,h3,h4,h5,h6{
  font-family: 'Cinzel';
}

h1{
  font-size: 24px;
  color: var(--primaryColor)
}

p{
  color: var(--paragraphColor);
}

.bg-blue{
  background-color: var(--primaryColor);
}

.topbar{
  width: 100%;
  height: 48px; 
  color: var(--whitecolor);
}

.flex{
  display: flex;
  justify-content: space-between;
  align-items: center;
}
</style>
