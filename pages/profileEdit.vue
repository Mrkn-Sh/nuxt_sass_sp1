<template>
  <div>
    <Header />
    <div class="profileEdit">
      <div class="profileEdit__title">프로필 변경</div>
        <div class="profile__avatar">
          <img src="" width="120" height="120" />
        </div> 
        <div class="profile__avatarUpdate">
          <a href="">프로필 이미지 변경</a>
        </div>
        <div class="profileEdit__recommend">
          추천 크기는 이거임  
        </div>
        <ul class="profileEdit__form">
          <li>
            <div class="profileEdit__form__rows">
              <div class="profileEdit__form__row__title">이름</div>
              <ul class="profileEdit__form__row__input">
                <li>
                  <input type="text" />
                </li>
                <li>
                  <input type="text" />
                </li>
              </ul>
            </div>
          </li>
          <li>
            <div class="profileEdit__form__row">
              <div class="profileEdit__form__row__title">
                프로필 텍스트
              </div>
              <div class="profileEdit__form__row__input">
                <textarea />
              </div>
            </div>
          </li>
        </ul>
        <div class="profileEdit__submit">
          <button class="btn btn--large btn--submit">설정</button>
        </div>
      </div>
    <Footer />
  </div>
</template>

<script>
import Header from "@/components/Header"
import Footer from "@/components/Footer"

import { defineComponent } from '@nuxtjs/composition-api'

export default defineComponent({
  components: {
    Header,
    Footer,
  },
    setup() {
        
    },
})
</script>
