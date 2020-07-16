<template>
  <div class="uk-container uk-container-large uk-margin-large-top">
    <div class="uk-alert-warning" uk-alert>
      <a class="uk-alert-close" uk-close></a>
      <p>以下專案因部分為單位內部網站，或尚未上線之網站，故以截取部分畫面呈現。</p>
    </div>
    <!-- <button type="button" @click="openLightbox">test</button> -->
    <div class="uk-grid-collapse uk-child-width-1-2@m uk-flex-between@m" uk-grid>
      <div
        class="uk-card uk-grid-collapse uk-card-default uk-margin-medium-bottom uk-child-width-1-2@s"
        uk-grid
      >
        <div class="uk-card-media-left uk-cover-container">
          <img src="../assets/img/M-s.jpg" alt uk-cover />
        </div>
        <div>
          <div class="uk-card-body">
            <h3 class="uk-card-title">Mober - 預約租車</h3>
            <ul class="uk-list uk-list-hyphen">
              <li>使用 Uikit 切板與效果套用</li>
              <li>依設計師圖檔切版，並將 icon 轉字體以利用</li>
            </ul>
          </div>
        </div>
      </div>
      <div
        class="uk-card uk-grid-collapse uk-card-default uk-margin-medium-bottom uk-child-width-1-2@s"
        uk-grid
      >
        <div class="uk-card-media-left uk-cover-container">
          <img src="../assets/img/TS-s.jpg" alt uk-cover />
        </div>
        <div>
          <div class="uk-card-body">
            <h3 class="uk-card-title">臺電秘書處網站</h3>
            <ul class="uk-list uk-list-hyphen">
              <li>使用 Uikit 製作 RWD 與效果套用</li>
              <li>使用 JQuery 變換佈景主題</li>
              <li>UI 繪製</li>
            </ul>
          </div>
        </div>
      </div>
      <div
        class="uk-card uk-grid-collapse uk-card-default uk-margin-medium-bottom uk-child-width-1-2@s"
        uk-grid
      >
        <div class="uk-card-media-left uk-cover-container">
          <img src="../assets/img/FG-s.jpg" alt uk-cover />
        </div>
        <div>
          <div class="uk-card-body">
            <h3 class="uk-card-title">臺北動質處快閃購網站</h3>
            <ul class="uk-list uk-list-hyphen">
              <li>依客戶需求、習慣繪製介面及製作網頁</li>
              <li>使用 Bootstrap 製作響應式網頁</li>
              <li>前台網站遵守無障礙 2A 規範</li>
            </ul>
            <div>
              <a href="#" class="uk-text-primary" uk-icon="image" title="更多畫面" @click.prevent="openLightbox('FG')"></a>
              <a href="https://flashgo.gov.taipei/" target="_blank" class="uk-text-primary" uk-icon="link" title="前往連結"></a>
            </div>
          </div>
        </div>
      </div>
      <div
        class="uk-card uk-grid-collapse uk-card-default uk-margin-medium-bottom uk-child-width-1-2@s"
        uk-grid
      >
        <div class="uk-card-media-left uk-cover-container">
          <img src="../assets/img/AFRC-s.jpg" alt uk-cover />
        </div>
        <div>
          <div class="uk-card-body">
            <h3 class="uk-card-title">後備指揮部網站</h3>
            <ul class="uk-list uk-list-hyphen">
              <li>依客戶需求繪製 wireframe 及製作網頁</li>
              <li>使用 Bootstrap 製作響應式網頁</li>
              <li>前台網站遵守無障礙 2A 規範</li>
            </ul>
            <div>
              <a href="#" class="uk-text-primary" uk-icon="image" title="更多畫面" @click.prevent="openLightbox('AFRC')"></a>
              <a href="https://afrc.mnd.gov.tw/AFRCWeb/" target="_blank" class="uk-text-primary" uk-icon="link" title="前往連結"></a>
            </div>
          </div>
        </div>
      </div>
      <div
        class="uk-card uk-grid-collapse uk-card-default uk-margin-medium-bottom uk-child-width-1-2@s"
        uk-grid
      >
        <div class="uk-card-media-left uk-cover-container">
          <img src="../assets/img/MOHW-s.jpg" alt uk-cover />
        </div>
        <div>
          <div class="uk-card-body">
            <h3 class="uk-card-title">衛服部互動式指標查詢網站維護</h3>
            <ul class="uk-list uk-list-hyphen">
              <li>依客戶需求繪製新功能介面進而製作網頁</li>
              <li>調整 css 寫法使網頁顯示更彈性</li>
              <li>影片剪輯置於首頁 banner 以強調網頁主題</li>
            </ul>
            <div>
              <a href="https://iiqs.mohw.gov.tw/index.aspx" target="_blank" class="uk-text-primary" uk-icon="link" title="前往連結"></a>
            </div>
          </div>
        </div>
      </div>
      <div
        class="uk-card uk-grid-collapse uk-card-default uk-margin-medium-bottom uk-child-width-1-2@s"
        uk-grid
      >
        <div class="uk-card-media-left uk-cover-container">
          <img src="../assets/img/YJ-s.jpg" alt uk-cover />
        </div>
        <div>
          <div class="uk-card-body">
            <h3 class="uk-card-title">青年就業領航計畫網站</h3>
            <ul class="uk-list uk-list-hyphen">
              <li>依客戶需求繪製介面及製作網頁</li>
              <li>使用 Bootstrap 製作響應式網頁</li>
            </ul>
            <div>
              <a href="https://bear-luo.github.io/YouthJobWeb/" target="_blank" class="uk-text-primary" uk-icon="link" title="前往連結"></a>
            </div>
          </div>
        </div>
      </div>
      <div
        class="uk-card uk-grid-collapse uk-card-default uk-margin-medium-bottom uk-child-width-1-2@s"
        uk-grid
      >
        <div class="uk-card-media-left uk-cover-container">
          <img src="../assets/img/SIX-s.jpg" alt uk-cover />
        </div>
        <div>
          <div class="uk-card-body">
            <h3 class="uk-card-title">6星集人資管理系統</h3>
            <ul class="uk-list uk-list-hyphen">
              <li>使用 Ace Admin 製作後台介面</li>
              <li>使用 AE 輸出 SVG 動畫</li>
            </ul>
          </div>
        </div>
      </div>
      <div
        class="uk-card uk-grid-collapse uk-card-default uk-margin-medium-bottom uk-child-width-1-2@s"
        uk-grid
      >
        <div class="uk-card-media-left uk-cover-container">
          <img src="../assets/img/Evaluate-s.jpg" alt uk-cover />
        </div>
        <div>
          <div class="uk-card-body">
            <h3 class="uk-card-title">臺北市動質處質借系統及員工平台</h3>
            <ul class="uk-list uk-list-hyphen">
              <li>依客戶需求繪製介面及製作網頁</li>
              <li>使用合適套件製作網頁所需功能及效果</li>
            </ul>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import UIkit from 'uikit'

export default {
  data () {
    return {
    }
  },
  methods: {
    openLightbox (para) {
      if (para === 'AFRC') {
        UIkit.lightboxPanel({
          items: [
            { source: 'img/AFRC-1.jpg', caption: '後備指揮部主網' },
            { source: 'img/AFRC-2.jpg', caption: '後備指揮部相關網站' },
            { source: 'img/AFRC-3.jpg', caption: '後備指揮部相關網站' },
            { source: 'img/AFRC-4.jpg', caption: '後備指揮部相關網站' }
          ]
        }).show()
      } else if (para === 'FG') {
        UIkit.lightboxPanel({
          items: [
            { source: 'img/FG-1.jpg', caption: '快閃購網站畫面' },
            { source: 'img/FG-2.jpg', caption: '快閃購網站畫面' }
          ]
        }).show()
      }
    }
  }
}
</script>

<style>
.uk-card {
  overflow: hidden;
}
.uk-card-media-left {
  box-shadow: 0 0 5px 1px rgba(0, 0, 0, 0.1);
  min-height: 200px;
}
.uk-card-body ul + div {
  position: absolute;
  right: 20px;
  bottom: 16px;
  text-align: right;
}
.uk-card-body a {
  border: 1px solid;
  width: 30px;
  height: 30px;
  line-height: 26px;
  border-radius: 50%;
  text-align: center;
  margin-left: 10px;
}
.uk-card-body a:hover {
  background-color: #1e87f0;
  border-color: #1e87f0;
}
.uk-card-body a:hover svg{
  color: #fff;
}
@media (min-width: 960px) {
  .uk-child-width-1-2\@m > * {
    width: calc(50% - 20px) !important;
  }
}
</style>
