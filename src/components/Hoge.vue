<script setup>
// 変数
const msg = 'Hello!'

// 関数
function log() {
  console.log(msg)
}

// JavaScriptのenum、これは無いのでエラーする
// enum ZeroOrOne {
//   Zero = 0,
//   One = 1,
// }
 
// console.log(ZeroOrOne[0]);
</script>

<template>
  <button @click="log">{{ msg }}</button>
</template>
