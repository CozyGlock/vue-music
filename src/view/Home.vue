<template>
  <div class="home">
    <div class="tips">
      <h2>iKun音乐播放器</h2>
      <p>操作方式：点击下方的黑色磁盘，选择 mp3 格式的乐曲，读取完毕后点击播放按钮</p>
    </div>
    <div class="copyright">
      <p>Author: 张傲</p>
      <p>Completion: 2024.3.21</p>
      <p>More: https://github.com/CozyGlock</p>
    </div>
    <player />
  </div>
</template>

<script>
import Player from "../components/Player";
export default {
  components: {
    Player
  }
};
</script>

<style scoped>
.home {
  display: flex;
  width: 100%;
  height: 100%;
  background-color: #ffedff;

  z-index: 0;

  position: relative;
  justify-content: center;
  align-items: center;
}
.tips {
  position: absolute;
  top: 10%;
  text-align: center;
}
.tips h2{
  font-size: 50px;
  font-family: 楷体;
  color: rgb(28, 128, 222);
}
.copyright{
  position: absolute;
  bottom: 10%;
  text-align: center;
}
</style>