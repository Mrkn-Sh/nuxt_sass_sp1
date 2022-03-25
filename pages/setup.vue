<template>
  <div>
    <Header />
    <div class="setup">
      <div class="setup__body">
        <dl class="setup__list">
          <dt>설정</dt>
          <dd>
            <button class="btn btn--medium btn--flat_orange">프로필</button>
          </dd>
          <dd>
            <button class="btn btn--medium btn--flat_orange">메일</button>
          </dd>
          <dd>
            <button class="btn btn--medium btn--flat_orange">비번</button>
          </dd>
          <dd>
            <button class="btn btn--medium btn--flat_orange">상담</button>
          </dd>
          <dd>
            <button class="btn btn--medium btn--flat_orange">이용내역</button>
          </dd>                
          <dd>
            <button class="btn btn--medium btn--flat_orange">프라이버시</button>
          </dd>
          <dd>
            <button class="btn btn--medium btn--flat_gray">로그아웃</button>
          </dd>
        </dl>
      </div>
    </div>
    <Footer />
  </div>
</template>

<script>
import { defineComponent } from '@nuxtjs/composition-api'
import Header from "@/components/Header"
import Footer from "@/components/Footer"

export default defineComponent({
  components: {
    Header,
    Footer,
  },
  setup() {
        
  },
})
</script>
