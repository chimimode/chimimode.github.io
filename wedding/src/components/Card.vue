<template>
  <div class="uk-width-1-1" style="visibility: hidden">
    <div class="card uk-text-center">
      <div>
        <h3>소중한 분들을<br />초대합니다</h3>
        <h4>
          음악으로 처음 만난 순간부터 함께한 모든 노래들이,<br />
          우리의 추억이 되고, 우리의 이야기가 되었습니다.<br />

          이제 같은 선율 속에서 평생을 연주하려 합니다.<br />
          인생이라는 긴 공연의 첫 무대에 <br />소중한 분들을 초대합니다.<br />
        </h4>
        <hr class="uk-divider-small" />
        <h5 class="lyrics">
          난 너의 세상을 함께 듣고 싶어<br />
          네 눈에 담은 걸 같이 보고 싶어<br />
          너의 맘 깊은 곳 작은 감정 하나도<br />
          내게 모두 다 전해지기를<br />

          &lt;LUCY - MP3&gt;
          <figure>
            <audio controls src="/MP3.mp3" controlsList="nodownload"></audio>
          </figure>
        </h5>
        <hr class="uk-divider-small" />
      </div>
      <div>
        <table>
          <tbody>
            <tr>
              <td>신사종, 안혜선의 장남</td>
              <td rowspan="1">동하</td>
            </tr>
            <tr>
              <td>최지우의 장녀</td>
              <td rowspan="1">지승</td>
            </tr>
          </tbody>
        </table>
        <!-- <img class="avatar" src="/img/avatar.png" /> -->
      </div>
    </div>
    <hr class="uk-divider-icon" />
  </div>
</template>

<style scoped>
.avatar {
  padding-top: 20px;
  image-rendering: pixelated;
}
.card {
  border: 1px solid rgba(var(--color-card-border), 0.8);
  border-radius: 600px 600px 0px 0px;
  width: 100%;
  max-width: 400px;
  margin: 0 auto;
  padding: 50px 0px 50px 0px;
}

table {
  margin-left: auto;
  margin-right: auto;
  font-weight: 600;
  color: rgba(var(--color-text-alpha), 0.8);
}

td {
  padding: 5px;
}

h4 {
  font-size: 0.9rem;
  line-height: 1.5rem;
}

.lyrics {
  color: rgba(var(--color-text-alpha), 0.717);
  letter-spacing: 1.5px;
  margin-top: 0;
  padding: 5px;
  font-size: 0.9rem;
  line-height: 1.5rem;
}

  audio {
    width: 143px;
  }

  audio::-webkit-media-controls-volume-slider {
    display: none !important;
  }

  audio::-webkit-media-controls-timeline-container {
    display: none !important;
  }

  audio::-webkit-media-controls-time-remaining-display {
    display: none !important;
  }

  audio::-webkit-media-controls-timeline {
    display: none !important;
  }
  audio::-webkit-media-controls-panel {
    background-color: #96bc7f;
    color: #96bc7f;
  }
  audio::-webkit-media-controls-enclosure {
    background-color: #96bc7f;
    color: #96bc7f;
  }
  figure {
      margin-bottom: 0;
  }
</style>
