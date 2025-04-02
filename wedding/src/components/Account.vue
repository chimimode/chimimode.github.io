<template>
  <div
    class="uk-width-1-1"
    uk-scrollspy="target: > div; cls: uk-animation-fade; delay: 220;"
  >
    <div>
      <h3>마음 전하실 곳</h3>
      <div class="uk-accordion-content">
        <p class="content-text">
          비대면으로 축하를 전하고자 하시는 분들을 위해 계좌번호를 기재하였습니다.
          너그러운 마음으로 양해 부탁드립니다.
        </p>
        <div>
          <ul uk-accordion="multiple: true">
            <li>
              <a class="uk-accordion-title">신랑측</a>
              <div class="uk-accordion-content">
                <dl class="uk-description-list uk-description-list-divider">
                  <dt>신랑</dt>
                  <dd>1002-565-573358<br />우리은행 신동하</dd>
                  <dt>신랑어머니</dt>
                  <dd>1002-441-166085<br />우리은행 안혜선</dd>
                </dl>
              </div>
            </li>
            <li>
              <a class="uk-accordion-title">신부측</a>
              <div class="uk-accordion-content">
                <dl class="uk-description-list uk-description-list-divider">
                  <dt>신부</dt>
                  <dd>655601-04-395879<br />국민은행 유지승</dd>
                  <dt>신부어머니</dt>
                  <dd>947801-01-144199<br />국민은행 최지우</dd>
                </dl>
              </div>
            </li>
          </ul>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.uk-accordion-content {
  color: rgba(var(--color-text-alpha), 0.815);
}

.uk-accordion-title {
  letter-spacing: 10px;
  font-size: 1rem;
  font-weight: 700;
  color: rgba(var(--color-text-alpha), 1);
}

.uk-description-list {
  background-color: #ffffff0c;
  border-radius: 10px;
  padding: 20px;
}

a:hover {
  color: rgba(var(--color-text-alpha), 0.655);
}

dt {
  letter-spacing: 5px;
  font-size: 0.9rem;
  font-weight: 700;
  color: rgba(var(--color-text-alpha), 0.815);
}

dd {
  font-size: 0.9rem;
  color: rgba(var(--color-text-alpha), 0.8);
}

.uk-accordion-title::before {
  background-image: url("data:image/svg+xml;charset=UTF-8,%3Csvg%20width%3D%2213%22%20height%3D%2213%22%20viewBox%3D%220%200%2013%2013%22%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%3E%0A%20%20%20%20%3Crect%20fill%3D%22%235e3b2f%22%20width%3D%2213%22%20height%3D%221%22%20x%3D%220%22%20y%3D%226%22%20%2F%3E%0A%20%20%20%20%3Crect%20fill%3D%22%235e3b2f%22%20width%3D%221%22%20height%3D%2213%22%20x%3D%226%22%20y%3D%220%22%20%2F%3E%0A%3C%2Fsvg%3E");
}

.uk-open > .uk-accordion-title::before {
  background-image: url("data:image/svg+xml;charset=UTF-8,%3Csvg%20width%3D%2213%22%20height%3D%2213%22%20viewBox%3D%220%200%2013%2013%22%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%3E%0A%20%20%20%20%3Crect%20fill%3D%22%235e3b2f%22%20width%3D%2213%22%20height%3D%221%22%20x%3D%220%22%20y%3D%226%22%20%2F%3E%0A%3C%2Fsvg%3E");
}
</style>
