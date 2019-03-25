<template lang="pug">
  article.report
    h1 不想瘦？胖子：想被當成普通人看待
    p.intro 許多胖子從小就胖，長大過程中常遭家人和同儕的指指點點。但胖子最大的期望不是瘦下來，而是得到與普通人同等的對待。
    p.intro 90 公斤的舞蹈老師黃冠潔在高中時愛上跳舞，是熱舞社裡最胖的女生，當她鼓起自信站上舞台時，卻有人說：「妳這麼胖，怎麼還敢跳舞？」
    button(type="button") 黃冠潔如何蛻變？
</template>

<script>
export default {
  name: 'BaseReport',
};
</script>

<style lang="scss">
.report {
  text-align: center;
  & h1 {
    font-size: 4.8rem;
    font-weight: 700;
    color: #fff;
    line-height: 1.5;
    margin-bottom: 32px;
  }
  button {
    margin-top: 40px;
    font-size: 2rem;
    line-height: 1.8;
    padding: 8px 24px;
    border-radius: 6px;
    background-color: #154d70;
    color: #ffe6be;
  }
}
.intro {
  font-size: 2.4rem;
  line-height: 1.8;
  color: #003152;
  padding-left: 19.375%;
  padding-right: 19.375%;
  & + .intro {
    margin-top: 16px;
  }
}
</style>
