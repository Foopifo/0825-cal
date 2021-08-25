<template>
  <div id="app">
    <!-- 사용자 정의 태그 - 1번 -->
  <Calculator/>
  </div>
</template>

<script>
// 하위 컴포넌트 가져오기
import Calculator from './components/Calculator.vue'

export default {
  name: 'App',
  components: {
    //하위 컴포넌트 이름 - 3번
    Calculator
  }
}
</script>

<style lang="scss">
@import "@/sass/app.scss";
</style>
