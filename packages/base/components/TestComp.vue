<template>
  <img src="~/assets/img/test.png" />
  <div id="asset-in-css"></div>
</template>

<style scoped>
img,
#asset-in-css {
  width: 512px;
  height: 512px;
}

#asset-in-css {
  background: url("@/assets/img/test.png") no-repeat;
}
</style>
