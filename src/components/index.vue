<template>
  <div id="container">
    <header>
      <nav>
        <div class="nav-left">
          <img src="../assets/img/icon4.png" alt="" />
          <img src="../assets/img/icon3.png" alt="" />
          <img src="../assets/img/icon2.png" alt="" />
          <img src="../assets/img/icon1.png" alt="" />
        </div>
        <div class="nav-right">
          <button>Connect</button>
        </div>
      </nav>
      <div class="info-img">
        <img src="../assets/img/rB.png" alt="" class="img5" />
        <div class="bth2">
          <img src="../assets/img/3-1.png" alt="" class="img6" />
          <div><button class="bth2-item">watch trailer</button></div>
        </div>
        <p style="color: #fff; line-height: 3.75rem; font-size: 1rem">
          Details about Rainbow2 are coming soon
        </p>
      </div>
    </header>
    <footer>
      <div class="content">
        <div class="content-left">
          <div class="item-text">
            <img src="../assets/img/rC.png" alt="" class="img7" />
            <p>
              Space Rainbow is your first venture into the galaxy to discover
              joy and rainbow puke. lt's the first, small step in unveiling our
              universe to collectors with dozens of spacecrafts designed by
              Burnt Toast.
            </p>
            <br />
            <p>
              What is your Rainbow in search of? Where is it going? How many
              other Rainbow are near you? Your Rainbow the key to answering
              these questions in our first step of revealing the universe.
            </p>
            <br />
            <p>
              All Rainbowwers can claim their Space Rainbow for free and receive
              its own unique appearance and competencies within their personal
              spacecraft. Stats like "bladder management" and "piloting
              ability"define a Rainbow competency in Space.
            </p>
            <button class="item-bth">Browse Space Doodles</button>
            <img src="../assets/img/1.png" alt="" class="img8" />
          </div>
        </div>
        <div class="content-right">
          <div class="content-right-img">
            <img src="../assets/img/3-2.png" alt="" class="img9" />
            <img src="../assets/img/3-3.png" alt="" class="img10" />
            <img src="../assets/img/组27.png" alt="" class="img11" />
          </div>

          <div class="item-text text-xy">
            <div class="img12"><img src="../assets/img/rD.png" alt="" /></div>

            <p>
              Rainbow are a ollection of 10,0o NFTs (non-fungible tokens)that
              are made up of hundreds of exciting visual traits designedby Burnt
              Toast. Hand-drawn Rainbow include skellys, cats,aliens, apes and
              mascots. The Rainbow collection also includesdozens of rare heads,
              costumes, and colorways of the artist'spalette.
            </p>
            <br />
            <p>
              The Rainbow universe is ever-expanding and new experienceslike
              Space Rainbow are only available to collectors. While theuniverse
              expands, our brand grows, and collectors can expectexclusive
              access to the latest products, merchandise and events through
              ownership.
            </p>
            <br />
            <p>
              Owning a Rainbow allows you to vote on community-drivenfeatures,
              products and events. This makes our roadmapcollaborative to be
              decided by the project founders andRainbow holders via the
              Rainbowbank. The Rainbowbank isour community treasury which boasts
              over s5m USD and isused to fund these experiences.
            </p>
            <button class="item-bth">Browse Space Doodles</button>
          </div>
        </div>
      </div>
      <div class="user">
        <div class="user-title">
          <p>YOUR FRENS THROUGH THE METAVARSE</p>
          <h1>The Rainbow Founders</h1>
        </div>
        <div class="user-message">
          <div class="user-message-item">
            <div><img src="../assets/img/11.png" alt="" /></div>
            <div>
              <h3>@evankeats</h3>
              <p class="usernmae">EVAN KEAST</p>
              <p>
                Also known as Tulip in the community, Evan is a Canadian-based
                product marketer and NFT consultant. Evan comes from Kabam
                Games(Net Marble), Dapper Labs,and CryptoKitties.
              </p>
            </div>
          </div>
          <div class="user-message-item">
            <div><img src="../assets/img/13.png" alt="" /></div>
            <div>
              <h3>@buirnttoast</h3>
              <p class="usernmae">SCOTT MARTIN</p>
              <p>
                Burnt Toast is the working alias forScott Martin, a Canadian-
                basedillustrator, designer, animator andmuralist. Burnt's past
                clients includeWhatsApp, Google, Snapchat, et al.
              </p>
            </div>
          </div>
          <div class="user-message-item">
            <div><img src="../assets/img/12.png" alt="" /></div>
            <div>
              <h3>@poopie</h3>
              <p class="usernmae">JORDAN CASTRO</p>
              <p>
                A blockchain builder since 2013.Poopie is known for bag holding
                andpreviously leading the CryptoKittiesteam at Dapper Labs.
              </p>
            </div>
          </div>
        </div>
        <div class="footer-text">
          <p>
            Created by the Rainbow Foundes with specal to our developer
            partners, West Coast NFT, our moderators, alfie, disclosure, and the
            support from community, our friends, families, and loved ones.
          </p>
          <p>For all press inquiries, please contact press@Rainbows.app</p>
        </div>
      </div>
    </footer>
  </div>
</template>

<script>
/*设置根元素<html>字体大小*/
function getRem() {
  var html = document.getElementsByTagName("html")[0]; /*获取标签元素<html>*/
  var oWidth =
    document.body.clientWidth ||
    document.documentElement
      .clientWidth; /*获取设备的宽度  ||后为兼容IE低版本写法*/
  html.style.fontSize =
    oWidth / 100 +
    "px"; /*设置根元素<html>字体大小   计算出的值 就相当于1rem;为什么？ 这就是rem单位的规定 1rem就等于根元素<html>字体大小*/
}

/*6.4: 为设计稿宽度640px; 若是750px的设计稿 只需要将6.4改为7.5即可。
 * 在手机屏幕宽度与设计稿一致时，即：oWidth = 750px 那么上面的计算 oWidth / 6.4 + "px" 结果就是100px;  html.style.fontSize = 100px
 *css3中规定 1rem就对应这<html>的font-size的大小，所以100px = 1rem 这样方便大家将px转化为rem 按照这个比例来设置字体大小、元素宽高、内外边距等的单位为rem;
 *举例：在设计稿中，某一行字体大小为14px,则我们需要在css文件中将对应的字体设置为0.14rem;
 *      在设计稿中，某一个元素宽高分别为 100px与20px;则我们需要在css中将对应的宽高设置为1rem与0.2rem;
 */

/*页面初始化调用getRem()*/
window.onload = function () {
  /*初始化*/
  getRem();
  /*getRem绑定监听*/
  window.addEventListener("resize", getRem, false);
};

export default {
  name: "index",
  components: {},
};
</script>

<style scoped>
@import url(../assets/css/style.css);

@media screen and (max-width: 768px) {
  * {
    font-size: 10px;
  }
  #container {
    width: 100%;
    height: 100%;
  }

  header {
    height: 100%;
  }

  nav {
    width: 100%;
    height: 40px;
    line-height: 40px;
  }

  .nav-left {
    margin: auto 0;
    flex: 2 !important;
  }

  .nav-left img {
    width: 46px;
    height: 20px;
  }

  .nav-right {
    flex: 1;
    height: 40px;
    line-height: 40px;
  }

  .nav-right button {
    display: inline-block;
    width: 60px;
    /* margin: 4px 0; */
    height: 24px;
    font-size: 12px;
    border-radius: 8px;
  }

  .info-img {
    box-sizing: border-box;
    width: 100%;
    height: 290px;
    margin: 0px;
    padding: 10px 0;
    position: relative;
  }

  .img5 {
    display: inline-block;
    margin-top: 10px 0;
    width: 140px;
    height: 32px;
  }

  .bth2 img {
    width: 300px;
    height: 200px;
  }

  .bth2 div {
    width: 74px;
    height: 26px;
    font-size: 10px;
    border-radius: 4px;
    position: absolute;
    top: 160px;
    left: 50px;
  }

  .bth2 .bth2-item {
    width: 74px;
    height: 26px;
    border-radius: 4px;
    font-size: 10px;
  }
  .bth2-item button {
  }

  .info-img p {
    margin-top: 8px;
  }

  footer {
    position: relative;
    padding-top: 30px;
  }

  .content {
    width: 80%;
    padding-bottom: 140px;
    margin: 0 auto;
    display: block;
  }

  .content-left,
  .content-right {
    width: 100%;
  }
  .content-left {
    position: relative;
  }

  .content-right {
    margin-top: 40px;
    margin-left: -20px;
  }

  .item-text {
    width: 100%;
  }

  .content-right-img {
    position: absolute;
    top: 20px;
    left: 210px;
  }

  .content .item-bth {
    font-size: 10px;
    margin: 8px 0px;
  }

  .img8 {
    width: 280px;
    height: 160px;
    display: block;
    margin: 0 auto;

    position: absolute;
    top: 230%;
  }

  .text-xy {
    width: 100%;
  }

  .text-xy p {
    width: 100%;
  }

  .img12 {
    width: 200px;
    height: 40px;
    margin: 10px auto;
  }

  .img12 img {
    width: 100%;
    height: 100%;
  }

  .user {
    width: 100%;
  }

  .user-title {
    line-height: 30px;
  }
  .user-title p {
    font-size: 8px;
  }
  .user-title h1 {
    font-size: 26px;
  }

  .user-message {
    display: block;
    width: 100%;
  }

  .user-message-item {
    display: flex;
    width: 90%;
    height: 100%;
    margin: 10px auto;
    box-shadow: 0 2px 12px 0 rgba(0, 0, 0, 0.1);
  }
  .user-message-item div:nth-child(1) {
    width: 60px;
    height: 60px;
    margin: auto auto;
  }

  .user-message-item div:nth-child(1) img {
    /* width: 100%;
    height: 100%; */
  }
  .user-message-item h3 {
    font: 16px 微软雅黑;
    line-height: 40px;
  }
  .user-message-item p {
    display: block;
    text-align: left;
    font-size: 12px;
    /* letter-spacing: 1px; */
    line-height: 20px;
  }
  .user-message .username {
    text-align: center;
  }
  .footer-text {
    width: 80%;
    /* height: 120px; */
    padding: 20px 0;
    margin: 0px auto;
    font-size: 10px;
    margin-top: 30px;
  }
}
</style>
