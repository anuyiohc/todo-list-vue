<script setup>
//js가 동적으로 제어하는 부분
</script>

<!-- html -->
<template>
  <h1>TODO LIST</h1>

  <input />
  <button>확인</button>

  <div class="todo-item">
  <div>코드짜기</div>
  <button>수정</button>
  </div>

</template>

<!-- css -->
<style scoped>
.todo-item{
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: center;
  border:1px solid gray;
}
</style>
