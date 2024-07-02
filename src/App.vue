<script setup lang="ts">
</script>

<template>
  <div class="left-panel">
    <div class="list">
      <div class="list-header">
        <h1>List 1</h1>
        <font-awesome-icon icon="chevron-down"/>
      </div>

      <div class="list-item">
        <input type="checkbox" />
        <span>sadf</span>
        <input class="list-item__input-number" type="number"/>
        <input class="list-item__input-color" type="color" />
      </div>
    </div>
  </div>
</template>

<style scoped>
.left-panel {
  width: 350px;
  padding: 20px;
  background-color: #fff;
  box-shadow: 0 2px 4px rgba(0,0,0,0.1);
  border-radius: 8px;
}

.list-header {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: center;
}

.list-item {
  display: flex;
  align-items: center;
  gap: .5rem;
}

.list-item__input-color {
  width: 40px;
  height: 40px;
  border: none;
}

.list-item__input-color,
.list-item__input-number {
  border: 1px solid #ccc;
  border-radius: 4px;
  padding: 5px;
}
</style>
