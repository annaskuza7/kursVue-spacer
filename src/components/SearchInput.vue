<template>
  <div class="searchWrapper">
    <input id="search" name="search" type="text" v-model="searchValue" @input="handleInput" />
  </div>
</template>

<script>
export default {
  name: "SearchInput",
};
</script>

<style lang="scss" scoped>
.searchWrapper {
  margin-top: 50px;
  display: flex;
  flex-direction: column;
  width: 250px;

  input {
    height: 30px;
    background: none;
    border: 0;
    border-bottom: 1px solid black;
  }
}
</style>
