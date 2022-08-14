<template>
  <div class="main">
    <section class="footer">
      <div class="content">
        <span>备案号：</span>
        <a href="https://beian.miit.gov.cn" target="_blank">鄂ICP备2021020526号-1</a>
      </div>
    </section>
  </div>
</template>

<style lang="scss">
.main {
  display: flex;
  flex-direction: column;
  justify-content: flex-end;
  height: 100vh;
  background: url("@/assets/bg.jpg") no-repeat;
  background-size: cover;
  background-attachment: fixed;
  overflow: hidden;
  .footer {
    padding: 20px 0;
    display: flex;
    align-items: center;
    justify-content: center;
    .content {
      display: inline-block;
    }
  }
}
</style>
