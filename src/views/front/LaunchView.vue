<template>
  <!-- 發起專案主要內容 -->
  <main>
    <!-- 開始提案區塊 -->
    <section
      class="bg-no-repeat bg-cover bg-center"
      style="
        background-image: url('./images/launch/launchBanner.png');
        height: 500px;
      "
    >
      <div
        class="container d-flex justify-content-center align-items-center h-100"
      >
        <div class="text-white text-center">
          <h2 class="mb-4">
            <img
              src="/images/launch/launchLogo.png"
              class="img-fluid"
              alt="DreamBoost Logo"
            />
          </h2>
          <p>啟動群眾力量，讓有價值的事物獲得更好的機會</p>
          <a
            href="#last"
            class="btn btn-primary btn-hover px-18 py-3 text-white border-secondary-light"
            >開始提案</a
          >
        </div>
      </div>
    </section>
    <!-- 為什麼需要募資區塊 -->
    <section class="position-relative overflow-hidden">
      <p
        class="position-absolute top-0 start-0 mb-0 fs-128 text-nowrap text-uppercase user-select-none"
        style="color: rgba(157, 212, 209, 0.45); letter-spacing: 0.48px"
      >
        Why is crowdfunding needed?
      </p>
      <span
        class="d-none d-md-block position-absolute start-md-n20 start-lg-n7 bottom-50 bottom-lg-n20 z-n1 bg-secondary-light rounded-circle"
        style="width: 724px; height: 724px"
      ></span>
      <div class="container">
        <div class="row justify-content-center">
          <div class="col-lg-6 col-xl-4 pt-25 pt-sm-28 pt-lg-31 pb-20 pb-lg-30">
            <div class="w-lg-75">
              <h3 class="fs-3 text-primary">為什麼需要群眾集資？</h3>
              <p class="mb-12 fs-6 text-primary-light">
                Why is crowdfunding needed?
              </p>
              <ul class="list-unstyled text-justify">
                <li class="mb-8">
                  <h4 class="d-flex align-items-center gap-2">
                    品牌擴散
                    <span
                      class="d-block flex-grow-1 bg-primary-light"
                      style="height: 1px"
                    ></span>
                  </h4>
                  <p class="fs-6 text-gray-500">
                    DreamBoost
                    擁有一群樂於嘗試、喜歡率先使用新產品和創意的會員，能夠以低成本又快速的方式協助您宣傳品牌和產品。透過前期的宣傳推廣，更能擴散品牌理念。
                  </p>
                </li>
                <li class="mb-8">
                  <h4 class="d-flex align-items-center gap-2">
                    取得資源
                    <span
                      class="d-block flex-grow-1 bg-primary-light"
                      style="height: 1px"
                    ></span>
                  </h4>
                  <p class="fs-6 text-gray-500">
                    有許多想要實現的計畫，但卻缺乏資源嗎？透過眾人的力量，不僅能在平台上獲得資金和物資支持，更能逐步實現計畫目標！
                  </p>
                </li>
                <li>
                  <h4 class="d-flex align-items-center gap-2">
                    測試市場
                    <span
                      class="d-block flex-grow-1 bg-primary-light"
                      style="height: 1px"
                    ></span>
                  </h4>
                  <p class="fs-6 text-gray-500 mb-0">
                    預先調查產品的特色是否足夠吸引人，並蒐集消費者對專案／產品的期待或建議，對未來的宣傳策略將會有顯著幫助！
                  </p>
                </li>
              </ul>
            </div>
          </div>
          <div class="col-lg-6 position-relative d-none d-lg-block">
            <span
              class="w-100 bg-primary position-absolute start-50 top-50 translate-middle z-n1 rounded-pill"
              style="height: 113%"
            ></span>
            <ul
              class="row justify-content-center gx-9 list-unstyled pt-30 pt-xxl-28"
            >
              <li class="col-5 col-xl-4 align-self-center position-relative">
                <div position-relative>
                  <img
                    src="/images/launch/launchWhyImgTwo.png"
                    class="img-fluid w-100 border border-3 border-top-0 border-start-0 border-secondary-light rounded-2 rounded-bottom-circle rounded-start-1"
                    alt="有三個人的手，其中一人帶著金色手錶"
                    style="box-shadow: 0px 4px 10px 0px rgba(57, 87, 132, 0.2)"
                  />
                  <p
                    class="position-absolute py-1 px-3 fs-4 bg-secondary-light text-primary fw-medium"
                    style="bottom: 15%"
                  >
                    取得資源
                  </p>
                </div>
                <img
                  src="/images/home/circle_white.svg"
                  class="img-fluid position-absolute start-50 translate-middle cuponcircle"
                  style="top: 140%"
                  alt=""
                />
              </li>
              <li class="col-5 col-xl-4">
                <div class="position-relative mb-9">
                  <img
                    src="/images/launch/launchWhyImg.png"
                    class="img-fluid w-100 border border-3 border-top-0 border-start-0 border-secondary-light rounded-2 rounded-bottom-circle rounded-start-1"
                    alt="一台 Mac 電腦的圖像"
                    style="box-shadow: 0px 4px 10px 0px rgba(57, 87, 132, 0.2)"
                  />
                  <p
                    class="position-absolute py-1 px-3 fs-4 bg-secondary-light text-primary fw-medium"
                    style="bottom: 15%"
                  >
                    品牌擴散
                  </p>
                </div>
                <div class="position-relative">
                  <img
                    src="/images/launch/launchWhyImgThree.png"
                    class="img-fluid w-100 border border-3 border-top-0 border-start-0 border-secondary-light rounded-2 rounded-bottom-circle rounded-start-1"
                    alt="兩個人正在講統計的圖表內容"
                    style="box-shadow: 0px 4px 10px 0px rgba(57, 87, 132, 0.2)"
                  />
                  <p
                    class="position-absolute py-1 px-3 fs-4 bg-secondary-light text-primary fw-medium"
                    style="bottom: 15%"
                  >
                    測試市場
                  </p>
                </div>
              </li>
            </ul>
          </div>
        </div>
      </div>
    </section>
    <!-- 選擇 DreamBoost 原因區塊 -->
    <section
      class="d-flex justify-content-center align-items-center py-28 bg-no-repeat bg-cover bg-center text-white"
      style="
        background-image: url('./images/launch/launchWhyBanner.png');
        background-attachment: fixed;
      "
    >
      <div class="container col-xl-6 text-xl-end">
        <h3 class="fs-24">
          為什麼選擇 DreamBoost 提案上架？
          <span class="d-block my-3 fs-6">Why Choose DreamBoost ?</span>
        </h3>
        <p class="fs-6">
          DreamBoost
          不僅歡迎新興品牌，更是傳統品牌改頭換面、甚至擴展客群的夢想推送地。
          <br />
          透過群眾集資，您能夠輕鬆實現改變消費者心中觀念，探索全新族群，並實踐品牌形象的全新展現。
        </p>
      </div>
    </section>
    <!-- 哪些人可以募資區塊 -->
    <section class="container mb-20 mb-lg-27">
      <div class="mb-16 text-lg-center">
        <h3 class="mb-4 pt-25 text-primary">
          哪些人 / 專案可以使用群眾集資？
          <span
            class="d-block fs-6 mt-1 text-primary-light"
            style="letter-spacing: 0.07px"
            >Who can use crowdfunding?</span
          >
        </h3>
        <p class="col-lg-7 mx-auto text-gray-700">
          無論您是個人還是企業／組織，我們歡迎各種提案類型，其中包括但不限於科技、設計、社會議題、在地發展、印刷出版、影視動畫、插畫漫畫、攝影、教育、旅遊、時尚、活動策劃、美容保養、藝術、遊戲、音樂、餐飲等領域。讓
          DreamBoost 與您攜手實現您的計畫吧！
        </p>
      </div>
      <ul class="row row-cols-1 row-cols-md-3 g-xl-14 list-unstyled">
        <li class="col">
          <div class="card border-0">
            <img
              src="/images/launch/launchUseOne.png"
              class="card-img-top object-fit-cover rounded"
              style="max-height: 250px"
              alt="..."
            />
            <div class="card-body p-6">
              <h5 class="card-title text-primary fs-4 text-center">
                原創型專案
              </h5>
              <p class="card-text mx-auto w-100 w-xl-75">
                由團隊自行發想、設計，並且符合提案服務說明內容者。
              </p>
            </div>
          </div>
        </li>
        <li class="col">
          <div class="card border-0">
            <img
              src="/images/launch/launchUseTwo.png"
              class="card-img-top object-fit-cover rounded"
              style="max-height: 250px"
              alt="..."
            />
            <div class="card-body p-6">
              <h5 class="card-title text-primary fs-4 text-center">
                倡議型專案
              </h5>
              <p class="card-text mx-auto w-100 w-xl-75">
                致力於特定社會公共議題，透過有針對性的措施推動其積極進展的計畫
              </p>
            </div>
          </div>
        </li>
        <li class="col">
          <div class="card border-0">
            <img
              src="/images/launch/launchUseThree.png"
              class="card-img-top object-fit-cover rounded"
              style="max-height: 250px"
              alt="..."
            />
            <div class="card-body p-6">
              <h5 class="card-title text-primary fs-4 text-center">
                預購型專案
              </h5>
              <p class="card-text mx-auto w-100 w-xl-75">
                由原創產品開發團隊委派代理商負責台灣銷售，在群眾集資平台上展開台灣地區的預購行銷活動
              </p>
            </div>
          </div>
        </li>
      </ul>
    </section>
    <!-- 流程說明區塊 -->
    <section class="container pb-25" id="last">
      <h3 class="d-lg-none text-primary mb-6">
        流程說明
        <span class="d-block fs-6 text-primary-light">Flow Description</span>
      </h3>
      <div class="row align-items-center">
        <div class="col-lg-6 order-last order-lg-first">
          <h3 class="d-none d-lg-block text-primary mb-6">
            流程說明
            <span class="d-block fs-6 text-primary-light"
              >Flow Description</span
            >
          </h3>
          <p class="fw-semibold">
            請確認以下事項，確保您符合 DreamBoost 提案人的身份
          </p>
          <ol class="list-unstyled">
            <li class="d-flex align-items-center gap-2 mb-9">
              <span
                class="align-self-start flex-shrink-0 border border-2 border-primary rounded-circle text-center text-primary"
                style="flex-basis: 24px; height: 24px"
                >1</span
              >
              <div>
                <p class="mb-0 text-gray-700 fs-18">
                  您已滿 18
                  歲是具備完全行為能力的自然人，或是合法登記的法人或團體
                </p>
                <p class="mb-0 fs-6 text-gray-600">
                  若提案者為未成年人，應由其法定代理人閱讀、暸解，才可進行提案流程。
                </p>
              </div>
            </li>
            <li class="d-flex align-items-center gap-2">
              <span
                class="align-self-start flex-shrink-0 border border-2 border-primary rounded-circle text-center text-primary"
                style="flex-basis: 24px; height: 24px"
                >2</span
              >
              <div>
                <p class="mb-0 text-gray-700 fs-18">
                  您是具有台灣居住地址、銀行帳戶及國籍的自然人或法人
                </p>
                <p class="col-9 mb-0 fs-6 text-gray-600">
                  目前 DreamBoost
                  只限定台灣用戶，國外單位提案必須有台灣分公司或代理人，並且由台灣代理人提交專案。
                </p>
              </div>
            </li>
          </ol>
          <VForm @submit="submit">
            <div
              class="position-relative d-flex align-items-center gap-2 mb-13"
            >
              <VField
                name="同意說明"
                type="checkbox"
                class="form-check-input"
                v-slot="{ field }"
                :value="true"
                :unchecked-value="false"
                :rules="checkConfirm"
              >
                <input
                  type="checkbox"
                  class="form-check-input align-self-start flex-shrink-0 mt-0"
                  style="width: 20px; height: 20px"
                  id="confirm"
                  name="同意說明"
                  v-bind="field"
                  :value="true"
                />
                <label for="confirm" class="form-check-label fs-18"
                  >您已符合以上敘述並同意 DreamBoost
                  <a href="#" class="text-decoration-underline"
                    >網站使用條款
                  </a>
                  及
                  <a href="#" class="text-decoration-underline">提案者合約 </a>
                </label>
              </VField>
              <ErrorMessage
                class="text-danger position-absolute top-100"
                name="同意說明"
              ></ErrorMessage>
            </div>
            <button
              type="submit"
              class="btn btn-primary d-block mx-auto ms-sm-0 px-18 py-3 text-white"
            >
              確認提案
            </button>
          </VForm>
        </div>
        <div class="col-lg-6">
          <img
            src="/images/launch/launchDescription.png"
            class="img-fluid object-fit-cover"
            alt="一張樹狀圖，上面描述著提交專案的流程"
          />
        </div>
      </div>
    </section>
  </main>
</template>

<script>
// // pinia 解構
// import { mapActions } from 'pinia';
// // Pinia Store 載入
// import memberStore from '@/stores/memberStore';
// mixins 引入
import mixinVeeValidate from '@/mixins/mixinVeeValidate';

export default {
  mixins: [mixinVeeValidate],

  methods: {
    // ...mapActions(memberStore, ['postCheckToken']),

    submit() {
      this.$router.push('/launch/outline');
    },
  },

  // mounted() {
  //   this.postCheckToken();
  // },
};
</script>
