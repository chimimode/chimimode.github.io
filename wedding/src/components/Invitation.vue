<template>
  <div class="uk-width-1-1" style="visibility: hidden">
    <div>
      <div class="uk-text-center">
        <div class="cloud-bg">
          <h1 class="logo">wedding<br />invitation</h1>
        </div>
        <img src="/main.png" />
      </div>
      <hr class="uk-divider-icon" />
      <div class="uk-text-center">
        <h3>
          신동하·유지승<br />
          결혼합니다
        </h3>
        <h4>
          2025년 5월 17일, 토요일 낮 12시 30분<br />
          SJ 쿤스트할레<br />
          <span class="content-text">(서울시 강남구 언주로 148길 5)</span>
        </h4>
        <hr class="uk-divider-icon" />
      </div>
    </div>
  </div>
</template>

<style scoped>
.logo {
  color: rgba(var(--color-text-alpha), 1);
  font-family: "Cafe24Meongi-B-v1.0";
}

.logo::before {
  content: "";
  position: absolute;
  transform: translateY(-20%) translateX(-50%);
  width: 20px;
  height: 20px;
  background-image: url("/img/flower-icon.png");
  background-size: contain;
  background-repeat: no-repeat;
}

.logo::after {
  content: "";
  position: absolute;
  transform: translateY(80%) translateX(-10%);
  width: 20px;
  height: 20px;
  background-image: url("/img/flower-icon.png");
  background-size: contain;
  background-repeat: no-repeat;
}
</style>
