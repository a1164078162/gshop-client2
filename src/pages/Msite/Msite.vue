<template>
  <div class="msite">
    <!--首页头部-->
    <Header title="6">
      <a class="header_search" slot="left">
        <i class="iconfont icon-sousuo"></i>
      </a>

      <a class="header_login" slot="right">
        <span class="header_login_text">登录|注册</span>
      </a>
    </Header>
    <!--首页导航-->
    <nav class="msite_nav border-1px">
      <div class="swiper-container">
        <div class="swiper-wrapper">
          <div class="swiper-slide">
            <a href="javascript:" class="link_to_food">
              <div class="food_container">
                <img src="./images/nav/1.jpg" />
              </div>
              <span>甜品饮品</span>
            </a>
            <a href="javascript:" class="link_to_food">
              <div class="food_container">
                <img src="./images/nav/2.jpg" />
              </div>
              <span>商超便利</span>
            </a>
            <a href="javascript:" class="link_to_food">
              <div class="food_container">
                <img src="./images/nav/3.jpg" />
              </div>
              <span>美食</span>
            </a>
            <a href="javascript:" class="link_to_food">
              <div class="food_container">
                <img src="./images/nav/4.jpg" />
              </div>
              <span>简餐</span>
            </a>
            <a href="javascript:" class="link_to_food">
              <div class="food_container">
                <img src="./images/nav/5.jpg" />
              </div>
              <span>新店特惠</span>
            </a>
            <a href="javascript:" class="link_to_food">
              <div class="food_container">
                <img src="./images/nav/6.jpg" />
              </div>
              <span>准时达</span>
            </a>
            <a href="javascript:" class="link_to_food">
              <div class="food_container">
                <img src="./images/nav/7.jpg" />
              </div>
              <span>预订早餐</span>
            </a>
            <a href="javascript:" class="link_to_food">
              <div class="food_container">
                <img src="./images/nav/8.jpg" />
              </div>
              <span>土豪推荐</span>
            </a>
          </div>
          <div class="swiper-slide">
            <a href="javascript:" class="link_to_food">
              <div class="food_container">
                <img src="./images/nav/9.jpg" />
              </div>
              <span>甜品饮品</span>
            </a>
            <a href="javascript:" class="link_to_food">
              <div class="food_container">
                <img src="./images/nav/10.jpg" />
              </div>
              <span>商超便利</span>
            </a>
            <a href="javascript:" class="link_to_food">
              <div class="food_container">
                <img src="./images/nav/11.jpg" />
              </div>
              <span>美食</span>
            </a>
            <a href="javascript:" class="link_to_food">
              <div class="food_container">
                <img src="./images/nav/12.jpg" />
              </div>
              <span>简餐</span>
            </a>
            <a href="javascript:" class="link_to_food">
              <div class="food_container">
                <img src="./images/nav/13.jpg" />
              </div>
              <span>新店特惠</span>
            </a>
            <a href="javascript:" class="link_to_food">
              <div class="food_container">
                <img src="./images/nav/14.jpg" />
              </div>
              <span>准时达</span>
            </a>
            <a href="javascript:" class="link_to_food">
              <div class="food_container">
                <img src="./images/nav/1.jpg" />
              </div>
              <span>预订早餐</span>
            </a>
            <a href="javascript:" class="link_to_food">
              <div class="food_container">
                <img src="./images/nav/2.jpg" />
              </div>
              <span>土豪推荐</span>
            </a>
          </div>
        </div>
        <!-- Add Pagination -->
        <div class="swiper-pagination"></div>
      </div>
    </nav>
    <!--首页附近商家-->
    <div class="msite_shop_list border-1px">
      <div class="shop_header">
        <i class="iconfont icon-xuanxiang"></i>
        <span class="shop_header_title">附近商家</span>
      </div>
      <div class="shop_container">
        <ul class="shop_list">
          <li class="shop_li border-1px">
            <a>
              <div class="shop_left">
                <img class="shop_img" src="./images/shop/1.jpg" />
              </div>
              <div class="shop_right">
                <section class="shop_detail_header">
                  <h4 class="shop_title">锄禾日当午，汗滴禾下土</h4>
                  <ul class="shop_detail_ul">
                    <li class="supports">保</li>
                    <li class="supports">准</li>
                    <li class="supports">票</li>
                  </ul>
                </section>
                <section class="shop_rating_order">
                  <section class="shop_rating_order_left">
                    <div class="star star-24">
                      <span class="star-item on"></span>
                      <span class="star-item on"></span>
                      <span class="star-item on"></span>
                      <span class="star-item half"></span>
                      <span class="star-item off"></span>
                    </div>
                    <div class="rating_section">3.6</div>
                    <div class="order_section">月售106单</div>
                  </section>
                  <section class="shop_rating_order_right">
                    <span class="delivery_style delivery_left">硅谷专送</span>
                    <span class="delivery_style delivery_right">准时达</span>
                  </section>
                </section>
                <section class="shop_distance">
                  <p class="shop_delivery_msg">
                    <span>¥20起送</span>
                    <span class="segmentation">/</span>
                    <span>配送费约¥5</span>
                  </p>
                </section>
              </div>
            </a>
          </li>
          <li class="shop_li border-1px">
            <a>
              <div class="shop_left">
                <img class="shop_img" src="./images/shop/2.jpg" />
              </div>
              <div class="shop_right">
                <section class="shop_detail_header">
                  <h4 class="shop_title ellipsis">锄禾日当午，汗滴禾下土</h4>
                  <ul class="shop_detail_ul">
                    <li class="supports">保</li>
                    <li class="supports">准</li>
                    <li class="supports">票</li>
                  </ul>
                </section>
                <section class="shop_rating_order">
                  <section class="shop_rating_order_left">
                    <div class="star star-24">
                      <span class="star-item on"></span>
                      <span class="star-item on"></span>
                      <span class="star-item on"></span>
                      <span class="star-item on"></span>
                      <span class="star-item off"></span>
                    </div>
                    <div class="rating_section">4.1</div>
                    <div class="order_section">月售106单</div>
                  </section>
                  <section class="shop_rating_order_right">
                    <span class="delivery_style delivery_left">硅谷专送</span>
                    <span class="delivery_style delivery_right">准时达</span>
                  </section>
                </section>
                <section class="shop_distance">
                  <p class="shop_delivery_msg">
                    <span>¥20起送</span>
                    <span class="segmentation">/</span>
                    <span>配送费约¥5</span>
                  </p>
                </section>
              </div>
            </a>
          </li>
          <li class="shop_li border-1px">
            <a>
              <div class="shop_left">
                <img class="shop_img" src="./images/shop/3.jpg" />
              </div>
              <div class="shop_right">
                <section class="shop_detail_header">
                  <h4 class="shop_title ellipsis">锄禾日当午，汗滴禾下土</h4>
                  <ul class="shop_detail_ul">
                    <li class="supports">保</li>
                    <li class="supports">准</li>
                    <li class="supports">票</li>
                  </ul>
                </section>
                <section class="shop_rating_order">
                  <section class="shop_rating_order_left">
                    <div class="star star-24">
                      <span class="star-item on"></span>
                      <span class="star-item on"></span>
                      <span class="star-item on"></span>
                      <span class="star-item off"></span>
                      <span class="star-item off"></span>
                    </div>
                    <div class="rating_section">3.2</div>
                    <div class="order_section">月售106单</div>
                  </section>
                  <section class="shop_rating_order_right">
                    <span class="delivery_style delivery_left">硅谷专送</span>
                    <span class="delivery_style delivery_right">准时达</span>
                  </section>
                </section>
                <section class="shop_distance">
                  <p class="shop_delivery_msg">
                    <span>¥20起送</span>
                    <span class="segmentation">/</span>
                    <span>配送费约¥5</span>
                  </p>
                </section>
              </div>
            </a>
          </li>
          <li class="shop_li border-1px">
            <a>
              <div class="shop_left">
                <img class="shop_img" src="./images/shop/4.jpg" />
              </div>
              <div class="shop_right">
                <section class="shop_detail_header">
                  <h4 class="shop_title ellipsis">锄禾日当午，汗滴禾下土</h4>
                  <ul class="shop_detail_ul">
                    <li class="supports">保</li>
                    <li class="supports">准</li>
                    <li class="supports">票</li>
                  </ul>
                </section>
                <section class="shop_rating_order">
                  <section class="shop_rating_order_left">
                    <div class="star star-24">
                      <span class="star-item on"></span>
                      <span class="star-item on"></span>
                      <span class="star-item on"></span>
                      <span class="star-item half"></span>
                      <span class="star-item off"></span>
                    </div>
                    <div class="rating_section">3.6</div>
                    <div class="order_section">月售106单</div>
                  </section>
                  <section class="shop_rating_order_right">
                    <span class="delivery_style delivery_left">硅谷专送</span>
                    <span class="delivery_style delivery_right">准时达</span>
                  </section>
                </section>
                <section class="shop_distance">
                  <p class="shop_delivery_msg">
                    <span>¥20起送</span>
                    <span class="segmentation">/</span>
                    <span>配送费约¥5</span>
                  </p>
                </section>
              </div>
            </a>
          </li>
        </ul>
      </div>
    </div>
  </div>
</template>

<script>
import Swiper from "swiper";
import "swiper/dist/css/swiper.min.css";
export default {
  mounted() {
    new Swiper(".swiper-container", {
      pagination: {
        el: ".swiper-pagination"
      },
      loop: true
    });
  }
};
</script>

<style lang="stylus" rel="stylesheet/stylus" scoped>
@import '../../common/stylus/mixins.styl'
.msite
  width 100%
  .msite_nav
    bottom-border-1px(#e4e4e4)
    margin-top 45px
    height 200px
    background #fff
    .swiper-container
      width 100%
      height 100%
      .swiper-wrapper
        width 100%
        height 100%
        .swiper-slide
          display flex
          justify-content center
          align-items flex-start
          flex-wrap wrap
          .link_to_food
            width 25%
            .food_container
              display block
              width 100%
              text-align center
              padding-bottom 10px
              font-size 0
              img
                display inline-block
                width 50px
                height 50px
            span
              display block
              width 100%
              text-align center
              font-size 13px
              color #666
      .swiper-pagination
        >span.swiper-pagination-bullet-active
          background #02a774
  .msite_shop_list
    top-border-1px(#e4e4e4)
    margin-top 10px
    background #fff
    .shop_header
      padding 10px 10px 0 10px
      .shop_icon
        margin-left 5px
        color #999
      .shop_header_title
        color #999
        font-size 14px
        line-height 20px
    .shop_container
      margin-bottom 50px
      .shop_list
        .shop_li
          bottom-border-1px(#f1f1f1)
          width 100%
          >a
            clearFix()
            display block
            box-sizing border-box
            padding 15px 8px
            width 100%
            .shop_left
              float left
              box-sizing border-box
              width 23%
              height 75px
              padding-right 10px
              .shop_img
                display block
                width 100%
                height 100%
            .shop_right
              float right
              width 77%
              .shop_detail_header
                clearFix()
                width 100%
                .shop_title
                  text_ellipsis()
                  float left
                  width 200px
                  color #333
                  font-size 16px
                  line-height 16px
                  font-weight 700
                  &::before
                    content '品牌'
                    display inline-block
                    font-size 11px
                    line-height 11px
                    color #333
                    background-color #ffd930
                    padding 2px 2px
                    border-radius 2px
                    margin-right 5px
                .shop_detail_ul
                  float right
                  margin-top 3px
                  .supports
                    float left
                    font-size 10px
                    color #999
                    border 1px solid #f1f1f1
                    padding 0 2px
                    border-radius 2px
              .shop_rating_order
                clearFix()
                width 100%
                margin-top 18px
                margin-bottom 8px
                .shop_rating_order_left
                  float left
                  color #ff9a0d
                  .star // 2x图 3x图
                    float left
                    font-size 0
                    .star-item
                      display inline-block
                      background-repeat no-repeat
                    &.star-48
                      .star-item
                        width 20px
                        height 20px
                        margin-right 22px
                        background-size 20px 20px
                        &:last-child
                          margin-right 0
                        &.on
                          bg-image('./images/stars/star48_on')
                        &.half
                          bg-image('./images/stars/star48_half')
                        &.off
                          bg-image('./images/stars/star48_off')
                    &.star-36
                      .star-item
                        width 15px
                        height 15px
                        margin-right 6px
                        background-size 15px 15px
                        &:last-child
                          margin-right 0
                        &.on
                          bg-image('./images/stars/star36_on')
                        &.half
                          bg-image('./images/stars/star36_half')
                        &.off
                          bg-image('./images/stars/star36_off')
                    &.star-24
                      .star-item
                        width 10px
                        height 10px
                        margin-right 3px
                        background-size 10px 10px
                        &:last-child
                          margin-right 0
                        &.on
                          bg-image('./images/stars/star24_on')
                        &.half
                          bg-image('./images/stars/star24_half')
                        &.off
                          bg-image('./images/stars/star24_off')
                  .rating_section
                    float left
                    font-size 10px
                    color #ff6000
                    margin-left 4px
                  .order_section
                    float left
                    font-size 10px
                    color #666
                    transform scale(0.8)
                .shop_rating_order_right
                  float right
                  font-size 0
                  .delivery_style
                    transform-origin 35px 0
                    transform scale(0.7)
                    display inline-block
                    font-size 12px
                    padding 1px
                    border-radius 2px
                  .delivery_left
                    color #fff
                    margin-right -10px
                    background-color #02a774
                    border 1px solid #02a774
                  .delivery_right
                    color #02a774
                    border 1px solid #02a774
              .shop_distance
                clearFix()
                width 100%
                font-size 12px
                .shop_delivery_msg
                  float left
                  transform-origin 0
                  transform scale(0.9)
                  width 200px
                  color #666
                .segmentation
                  color #ccc
width 100%, .header // 头部公共css
  background-color #02a774
  position fixed
  z-index 100
  left 0
  top 0
  width 100%
  height 45px
  .header_search
    position absolute
    left 15px
    top 50%
    transform translateY(-50%)
    width 10%
    height 50%
    .iconfont
      font-size 22px
      color #fff
  .header_title
    position absolute
    top 50%
    left 50%
    transform translate(-50%, -50%)
    width 30%
    color #fff
    font-size 22px
    text-align center
.profile-number
  margin-top 45.5px
  .profile-link
    clearFix()
    position relative
    display block
    background #02a774
    padding 20px 10px
    .profile_image
      float left
      width 60px
      height 60px
      border-radius 50%
      overflow hidden
      vertical-align top
      .icon-person
        background #e4e4e4
        font-size 62px
    .user-info
      float left
      margin-top 8px
      margin-left 15px
      p
        font-weight 700
        font-size 18px
        color #fff
        &.user-info-top
          padding-bottom 8px
        .user-icon
          display inline-block
          margin-left -15px
          margin-right 5px
          width 20px
          height 20px
          .icon-mobile
            font-size 30px
            vertical-align text-top
        .icon-mobile-number
          font-size 14px
          color #fff
    .arrow
      width 12px
      height 12px
      position absolute
      right 15px
      top 40%
      .icon-jiantou1
        color #fff
        font-size 5px
.profile_info_data
  bottom-border-1px(#e4e4e4)
  width 100%
  background #fff
  overflow hidden
  .info_data_list
    clearFix()
    .info_data_link
      float left
      width 33%
      text-align center
      border-right 1px solid #f1f1f1
      .info_data_top
        display block
        width 100%
        font-size 14px
        color #333
        padding 15px 5px 10px
        span
          display inline-block
          font-size 30px
          color #f90
          font-weight 700
          line-height 30px
      .info_data_bottom
        display inline-block
        font-size 14px
        color #666
        font-weight 400
        padding-bottom 10px
    .info_data_link:nth-of-type(2)
      .info_data_top
        span
          color #ff5f3e
    .info_data_link:nth-of-type(3)
      border 0
      .info_data_top
        span
          color #6ac20b
.profile_my_order
  top-border-1px(#e4e4e4)
  margin-top 10px
  background #fff
  .my_order
    display flex
    align-items center
    padding-left 15px
    >span
      display flex
      align-items center
      width 20px
      height 20px
      >.iconfont
        margin-left -10px
        font-size 30px
      .icon-order-s
        color #02a774
      .icon-jifen
        color #ff5f3e
      .icon-vip
        color #f90
      .icon-fuwu
        color #02a774
    .my_order_div
      width 100%
      border-bottom 1px solid #f1f1f1
      padding 18px 10px 18px 0
      font-size 16px
      color #333
      display flex
      justify-content space-between
      span
        display inline-block
      .my_order_icon
        float right
        width 10px
        height 10px
        .icon-jiantou1
          color #bbb
          font-size 10px
</style>
