<template>
  <div id="app" style="">

    <!-- Nav -->
    <main class="app-main">
      <router-view/>
    </main>

    <footer class="app-footer">
      <div class="footer-line">基于 <a href="https://uptimerobot.com/" target="_blank" rel="noopener noreferrer" class="link-green">UptimeRobot</a> 接口制作，检测频率 5 分钟</div>
      <div class="footer-line">© 2020 <a href="https://gw124.com/" target="_blank" rel="noopener noreferrer" class="link-green">STATUSLIVE.GW124.COM</a></div>
    </footer>
  </div>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  min-height: 100vh;
  display: flex;
  flex-direction: column;
  
}

body{
  background: #eeeeee;
}

.app-main{
  flex: 1;
}

.app-footer{
  position: fixed;
  left: 0;
  right: 0;
  bottom: 0;
  padding: 8px 8px;
  text-align: center;
  color: #6b7280;
  background: #eeeeee;
  box-shadow: 0 -1px 0 rgba(0,0,0,0.06);
  line-height: 1.6;
  z-index: 2147483647;
}

.app-footer .footer-line{
  font-size: 12px;
  margin: 2px 0;
}

.app-footer a{ text-decoration: none; }

.app-footer a.link-green{
  color: #16a34a;
  font-weight: 600;
}

.app-footer a:hover{ text-decoration: underline; }

</style>
