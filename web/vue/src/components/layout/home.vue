<template lang='pug'>
  section.contain.grd-row
    .grd-row-col-3-6(v-html='left')
    .grd-row-col-3-6.txt--center
      img(src='static/bot.jpg')
      p
        em 
</template>

<script>
import marked from '../../tools/marked';

const left = marked(`

## TradeBot

This is a Bitcoin trading bot and backtesting platform that
connects to popular Bitcoin exchanges. It checks the market data for the prices and after the analysis based on historical data it trades to get you as much profit as possible.

We can backtest the platform by importing different datasets to simulate the performance.



`);

export default {
  data: () => {
    return {
      left
    }
  }
}
</script>
