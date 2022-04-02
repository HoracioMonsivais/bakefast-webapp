<template>
  <router-view/>
</template>

<style>
* {
  margin: 0;
  box-sizing: border-box;
}

:root {
  --Typography: 'Roboto', sans-serif;
  --Primary-color: #9600FF;
  --Secondary-color: #4B0080;
  --Button-action-color: #CB80FF;
  --Decoration-color: #F4E7FD;
}

body {
  font-family: var(--Typography);
  padding: var(--Padding-container);
}
</style>
