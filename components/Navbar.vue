<template>
  <div class="navbar">
    <div class="links">
      <a href="/"> Dynamic </a>
      <a href="/vueUse"> vueUse </a>
      <a href="/Vue3SketchRuler"> 尺规组件 </a>
      <a href="/uitest"> UI组件库测试 </a>
    </div>
    <a
      href="https://github.com/majun2232/nuxt3-test"
      target="_blank"
      rel="noopener"
      class="gh-button"
    >
      GitHub
    </a>
  </div>
</template>

<style>
.navbar {
  display: flex;
  justify-content: space-between;
  padding: 0 8px;
  padding-top: 16px;
  background-color: #8f8f70;
}

.navbar .links {
  display: flex;
}

.links a {
  display: block;
  padding: 20px 32px;
  color: #555522;
  margin: 0 8px;
  text-decoration: none;
  font-weight: 600;
  background-color: #b4b48c;
  border-top-left-radius: 8px;
  border-top-right-radius: 8px;
}

.links a:hover {
  color: #003c3c;
}

.links .nuxt-link-exact-active,
.links .nuxt-link-exact-active:hover {
  color: #003c3c;
  background-color: #efefe6;
}

.gh-button {
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 0 16px;
  border-radius: 8px;
  font-weight: 500;
  font-size: 14px;
  text-decoration: none;
  background-color: #003c3c;
  color: #efefe6;
  margin-bottom: 16px;
}

.gh-button:hover {
  color: #fff;
  background-color: #032a2a;
}
</style>
