<script setup></script>
<template>
  <div class="container">
    <h2>Mais do álbum</h2>
    <div class="songs">
      <div class="line">
        <img src="https://i.ibb.co/zVbqkzLm/ab67616d0000b27359ae8cf65d498afdd5585634.jpg" alt="" />
        <p>Peppers (feat. Tommy Genesis)</p>
      </div>
      <div class="line">
        <img src="https://i.ibb.co/zVbqkzLm/ab67616d0000b27359ae8cf65d498afdd5585634.jpg" alt="" />
        <p>Why'd You Only Call Me When Yo...</p>
      </div>
      <div class="line">
        <img src="https://i.ibb.co/zVbqkzLm/ab67616d0000b27359ae8cf65d498afdd5585634.jpg" alt="" />
        <p>Peppers (feat. Tommy Genesis)</p>
      </div>
      <div class="line">
        <img src="https://i.ibb.co/zVbqkzLm/ab67616d0000b27359ae8cf65d498afdd5585634.jpg" alt="" />
        <p>Why'd You Only Call Me When Yo...</p>
      </div>
      <div class="line">
        <img src="https://i.ibb.co/zVbqkzLm/ab67616d0000b27359ae8cf65d498afdd5585634.jpg" alt="" />
        <p>Peppers (feat. Tommy Genesis)</p>
      </div>
      <div class="line">
        <img src="https://i.ibb.co/zVbqkzLm/ab67616d0000b27359ae8cf65d498afdd5585634.jpg" alt="" />
        <p>Why'd You Only Call Me When Yo...</p>
      </div>
    </div>
  </div>
</template>
<style scoped>
.container {
  display: flex;
  flex-direction: column;
  width: 20vw;
  background-color: #1e1e1e;
  border-radius: 7px;
  height: 255px;
  margin-right: 10px;
  color: #e6e8ee;
  padding: 15px;
}

h2 {
  font-size: 18px;
}

.songs {
  overflow-y: scroll;
}

.line {
  display: flex;
  align-items: center;
  gap: 17px;
  margin: 10px 0;
  height: 60px;
  width: 95%;
  border-radius: 7px;
  padding: 5px;
}

.line:hover {
    background-color: var(--darker-gray);
}

img {
  width: 50px;
  height: 50px;
  border-radius: 7px;
}
</style>
