<template>
  <div>
    <div>
      <div>Img 1 (&lt;img :src="'/img/' + 1 + '.webp'" /&gt;)</div>
      <img :src="'/img/' + 1 + '.webp'" />
    </div>
    <div>
      <div>Img 2 (&lt;img src="/img/2.webp" /&gt;)</div>
      <img src="/img/2.webp" />
    </div>
  </div>
</template>
