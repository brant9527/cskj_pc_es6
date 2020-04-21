<template>
  <div class="content">
    <div class="download">
      <div class="download-wrap">
        <div class="download-logo"> <img src="~/static/img/logo.png"
               alt=""></div>
        <div class="download-parts">
          <div class="ewm">
            <el-popover>
              <img class="ewm-big"
                   src="~/static/img/ewm.png"
                   alt="">
              <div slot="reference">
                <img class="ewm-small"
                     src="~/static/img/ewm.png"
                     alt="">
                <div>安卓下载</div>
              </div>
            </el-popover>

          </div>
          <div class="ewm">
            <el-popover>
              <img class="ewm-big"
                   src="~/static/img/ewm.png"
                   alt="">
              <div slot="reference">
                <img class="ewm-small"
                     src="~/static/img/ewm.png"
                     alt="">
                <div>安卓下载</div>
              </div>
            </el-popover>

          </div>
          <div class="ewm">
            <el-popover>
              <img class="ewm-big"
                   src="~/static/img/ewm.png"
                   alt="">
              <div slot="reference">
                <img class="ewm-small"
                     src="~/static/img/ewm.png"
                     alt="">
                <div>安卓下载</div>
              </div>
            </el-popover>

          </div>
        </div>

      </div>
      <div class="phone"></div>
    </div>
  </div>
</template>
<script >
</script>
<style lang="scss" scoped>
.content {
  width: 100%;
  height: 800px;
  background-color: #fff;

  .download {
    width: 1300px;
    height: 800px;
    background-color: #fff;
    display: flex;
    justify-content: space-between;
    margin: 0 auto;
    .download-wrap {
      margin-top: 240px;
      .download-logo {
        img {
          width: 422px;
        }
      }
      .download-parts {
        display: flex;
        justify-content: space-between;
        .ewm {
          margin: 10px 0;
          text-align: center;
          img {
            width: 81px;
            height: 81px;
            margin: 0 auto;
          }
          .ewm-small {
            margin: 10px 0;
          }
          .ewm-big {
          }
        }
      }
    }
    .phone {
      width: 768px;
      height: 609px;
      background-image: url("/img/phone.png");
      background-size: cover;
      margin-top: 107px;
    }
  }
}
</style>