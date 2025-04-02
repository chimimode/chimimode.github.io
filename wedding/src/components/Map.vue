<template>
  <div
    class="uk-width-1-1"
    uk-scrollspy="target: > h3, div; cls: uk-animation-fade; delay: 220;"
  >
    <div>
      <h3>오시는 길</h3>
      <div class="uk-accordion-content">
        <p>
          <span class="header-text">SJ 쿤스트할레</span><br />
          <span class="content-text">서울시 강남구 언주로 148길 5</span>
        </p>
        <p>
          <span class="content-text"
            ><span class="uk-label uk-label-success">7호선</span> 강남구청역 3번출구에서
            도보 15분<br /><span class="uk-label uk-label-success">7호선</span> 강남구청역
            3번출구에서 셔틀버스 운행</span
          >
        </p>
        <div>
          <iframe
            src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3164.468243811864!2d127.0323070759187!3d37.52045807205049!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x357ca38b810fa6f5%3A0x8e2970ebe1107a86!2zU0og7L-k7Iqk7Yq47ZWg66CI!5e0!3m2!1sko!2skr!4v1738509908466!5m2!1sko!2skr"
            width="100%"
            height="300"
            style="border: 0"
            allowfullscreen=""
            loading="lazy"
            referrerpolicy="no-referrer-when-downgrade"
          ></iframe>
        </div>
        <p>
          <span class="header-text">주차안내</span><br />
          <span class="content-text"
            >⓵ 예식장의 주차장이 협소합니다. 현장에서 발렛 주차를 지원해 드리니 자차로
            이동하시는 분들께서는 여유롭게 도착해 주시길 부탁드립니다.<br />
            ⓶ [강남구청역 3번 출구]에서 셔틀버스를 운행합니다.</span
          >
        </p>
      </div>
    </div>
    <hr class="uk-divider-icon" />
  </div>
</template>

<style scoped>
.header-text {
  font-weight: 600;
}

.uk-accordion-content {
  color: rgba(var(--color-text-alpha), 0.815);
}

.uk-label {
  font-size: 0.8rem;
  padding: 0 5px;
  border-radius: 10px;
  vertical-align: inherit;
  margin: 0 5px 0 0;
}
</style>
