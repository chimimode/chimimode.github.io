<script setup>
  import { ref } from 'vue'

  const imageList = ref([]);
  imageList.value = [...new Array(18)].map((photo, index) => {
    return {
      index: index,
      path: `/gallery/${index + 1}.jpg`
    }
  });

  const imageList2 = ref([]);
  imageList2.value = [...new Array(16)].map((photo, index) => {
    return {
      index: index,
      path: `/gallery2/${index + 1}.jpg`
    }
  });
</script>

<template>
  <div
    class="uk-width-1-1"
    uk-scrollspy="target: > h3, div; cls: uk-animation-fade; delay: 220;"
  >
    <div>
      <h3>갤러리</h3>
      <!--slide1-->
      <div class="uk-position-relative uk-visible-toggle uk-light"
           tabindex="-1"
           uk-slider="autoplay: false">
        <ul class="uk-slider-items uk-child-width-1-1">
          <li class="photos" v-for="image in imageList">
            <img :src="image.path" />
            <div class="uk-position-center uk-panel"></div>
          </li>
          <!--li>
            <img src="/img/gallery/1.jpeg" />
            <div class="uk-position-center uk-panel"></div>
          </!--li>
          <li>
            <img src="/img/gallery/2.jpeg" />
            <div class="uk-position-center uk-panel"></div>
          </li>
          <li>
            <img src="/img/gallery/3.jpeg" />
            <div class="uk-position-center uk-panel"></div>
          </li-->
        </ul>

        <a class="uk-position-center-left uk-position-small uk-hidden-hover"
           href="#"
           uk-slidenav-previous
           uk-slider-item="previous"></a>
        <a class="uk-position-center-right uk-position-small uk-hidden-hover"
           href="#"
           uk-slidenav-next
           uk-slider-item="next"></a>
      </div>
      <!--slide2-->
      <div class="uk-position-relative uk-visible-toggle uk-light "
           tabindex="-1"
           uk-slider="autoplay: true"
           style="margin-top: 20px;"
           >
        <ul class="uk-slider-items uk-child-width-1-1">
          <li class="photos" v-for="image2 in imageList2">
            <img :src="image2.path" />
            <div class="uk-position-center uk-panel"></div>
          </li>
        </ul>

        <a class="uk-position-center-left uk-position-small uk-hidden-hover"
           href="#"
           uk-slidenav-previous
           uk-slider-item="previous"></a>
        <a class="uk-position-center-right uk-position-small uk-hidden-hover"
           href="#"
           uk-slidenav-next
           uk-slider-item="next"></a>
      </div>

    </div>
    <hr class="uk-divider-icon" />
  </div>
</template>

<style scoped>
.uk-label {
  font-size: 0.8rem;
  padding: 0 5px;
  border-radius: 10px;
  vertical-align: inherit;
  margin: 0 5px 0 0;
}

  .photos {
    display: flex;
    justify-content: center;
  }

  .photos > img {
    height: 250px !important;
    object-fit: contain;
  }
</style>
