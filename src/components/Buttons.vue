<template>
    <div class="grid-container">
        <div class="grid-item">C</div>
        <div class="grid-item">+/-</div>
        <div class="grid-item">%</div>
        <div class="grid-item">/</div>
        <div class="grid-item">7</div>
        <div class="grid-item">8</div>
        <div class="grid-item">9</div>
        <div class="grid-item">x</div>
        <div class="grid-item">4</div>
        <div class="grid-item">5</div>
        <div class="grid-item">6</div>
        <div class="grid-item">-</div>
        <div class="grid-item">1</div>
        <div class="grid-item">2</div>
        <div class="grid-item">3</div>
        <div class="grid-item">+</div>
        <div class="grid-item">0</div>
        <div class="grid-item">.</div>
        <div class="grid-item">del</div>
        <div class="grid-item">=</div>
    </div>
</template>

<script>
export default {
    name: "Buttons"
}
</script>

<style>
.grid-container {
  display: grid;
  margin: auto;
  width: 31%;
  grid-template-columns: auto auto auto auto;
  background-color: black;
  padding: 3px;
}
.grid-item {
  background-color: white;
  border: 1px solid rgba(0, 0, 0, 0.8);
  padding: 20px;
  font-size: 30px;
  text-align: center;
}
</style>