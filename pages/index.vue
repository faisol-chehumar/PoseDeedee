<template>
  <section class="container">
    <a-layout>
      <a-layout-header class="top-nav">
        <a-row type="flex" justify="center">
          <a-col :span="4">
            <div class="logo">
              <span class="-img"></span>
              <span class="-title">PERFECT SNAP</span>
            </div>
          </a-col>
          <a-col :span="3" :offset="9">แอพเราทำงานอย่างไร</a-col>
          <a-col :span="3">เกี่ยวกับเรา</a-col>
          <a-col :span="3">รับข่าวสาร</a-col>
        </a-row>
      </a-layout-header>
      <a-layout-content>Content</a-layout-content>
      <a-layout-footer class="footer">
        Made with
        <a-icon type="heart" theme="twoTone" two-tone-color="#eb2f96" />
        by Pose-D team.
      </a-layout-footer>
    </a-layout>
  </section>
</template>

<style>
.logo {
  display: flex;
  align-items: center;
}

.logo .-img {
  background-image: url('~assets/logo.png');
  background-size: cover;
  width: 4rem;
  height: 4rem;
  display: inline-block;
}

.logo .-title {
  margin-left: 1rem;
  font-size: 1.5rem;
  font-weight: 800;
  font-family: 'Oswald';
}

.top-nav.ant-layout-header {
  background: #eee;
  padding: 0.5rem 0;
  height: 5rem;
  border-bottom: 1px solid #ddd;
}

.container .ant-layout {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  text-align: center;
  background: transparent;
}

.footer {
  border-top: 1px solid #ddd;
}
</style>
