<template lang='pug'>
  section.contain.grd-row
    .grd-row-col-3-6(v-html='left')
    .grd-row-col-3-6.txt--center
      
</template>

<script>
import marked from '../../tools/marked';

const left = marked(`

## Gekko

This bot is a Bitcoin trading bot and backtesting platform that
connects to popular Bitcoin exchanges. It supports multiple exchanges and you can use them by adding the api
keys to your exchanges.


`);

export default {
  data: () => {
    return {
      left
    }
  }
}
</script>
