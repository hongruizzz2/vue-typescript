<script setup lang="ts">

</script>

<template>
<div className="App">
        <p>
          欢迎使用vuact-cli脚手架创建Vue3+TS
        </p>
        <p>
          Author：洪睿
        </p>
        <a
            href="https://github.com/hongruizzz2"
            target="_blank"
            rel="noopener noreferrer"
        >
          项目Github地址
        </a>
      </div>
</template>

<style scoped>
.App {
    display: flex;
    justify-content: center;
    align-content: center;
    height: 100vh;
    flex-direction: column;
}

.App p {
    font-size: 50px;
    display: inline-block;
    padding: 10px 20px; /* 根据需要调整 */
    background-image: linear-gradient(45deg, green 0%, deepskyblue 100%); /* 渐变颜色 */
    border-radius: 5px; /* 圆角 */
    color: white; /* 文字颜色 */
    text-decoration: none; /* 去掉下划线 */
    border-radius: 5px;
    text-align: center;
}

.App a {
    text-align: center;
}
</style>
