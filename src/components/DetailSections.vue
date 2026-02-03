<template>
  <div>
    <div class="box3">
      <div class="left">
        <img src="../assets/images/box3-wqq02iLp.png" alt="" />
      </div>
      <div class="right">
        <div class="tips">FINGERPRINT CLONE BROWSER:JUST USE AI CLOUD</div>
        <div class="title">指纹分身浏览器，就用AI Cloud</div>
        <div class="subTitle">
          业界最精准的指纹模拟与分身隔离技术，纯净、独享的
          IP设备与海外专线加速，致力于为跨境人解决多账号防
          关联与账号矩阵安全运营问题
        </div>
        <a href="https://ai-matrix.zhuliuhuoke.com/cooperation" target="_blank" class="btn">联系我们</a>
      </div>
    </div>

    <div class="box4">
      <div class="right">
        <div class="tips">
          AI CLOUD RPA + CHATGPT HAS AN INFINITE SPACE FOR IMAGINATION.
        </div>
        <div class="title">AI Cloud RPA + ChatGPT无限可能的想象空间</div>
        <div class="subTitle">
          如果把AI Cloud RPA比做人手的话，ChatGPT就是人脑
          人手+人脑，便有了无限可能的想象空间在您的自动化流程脚本中，可以通过ChatGPT生成智能评论，可以对抓取的数据通过ChatGPT进行智能判断与分析，机器人不仅能够完成枯燥、重复的工作，更能够帮助您智能的工作
        </div>
        <a href="https://ai-matrix.zhuliuhuoke.com/cooperation" target="_blank" class="btn">联系我们</a>
      </div>
      <div class="left">
        <img src="../assets/images/box4-CylWf_Oz.png" alt="" />
      </div>
    </div>

    <div class="box3">
      <div class="left">
        <img src="../assets/images/box3-2-D9E8bbSG.png" alt="" />
      </div>
      <div class="right">
        <div class="tips">Multi-platform marketing</div>
        <div class="title">热门社媒多平台登录 打造线上多平台矩阵体系</div>
        <div class="subTitle">
          线上多平台一键登录，围绕品牌，个人ip打造品牌，
          达人矩阵生态，实现线上互联网霸屏，对建立客户心
          智效果明显，通过线上多平台矩阵体系，建立属于你 的互联网商业流量闭环。
        </div>
        <a href="https://ai-matrix.zhuliuhuoke.com/cooperation" target="_blank" class="btn">联系我们</a>
      </div>
    </div>

    <div class="box4">
      <div class="right">
        <div class="tips">
          AIGC content marketing Popular popular content is generated in one
          click
        </div>
        <div class="title">AIGC内容营销 热门爆款内容一键生成</div>
        <div class="subTitle">
          aigc一键热门视频文案生成，热门社媒平台短视频一键
          下载，一键创作，灵感匮乏，内容创造一招解决，热门
          爆款文案，新鲜创意视频统统一键解决，提高内容生产
          效率，提升营销效率，解决您在社媒上营销的后顾之忧。
        </div>
        <a href="https://ai-matrix.zhuliuhuoke.com/cooperation" target="_blank" class="btn">联系我们</a>
      </div>
      <div class="left">
        <img src="../assets/images/box4-2-fZsZ3kHz.png" alt="" />
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "DetailSections",
  mounted() {
    this.observeElements();
  },
  methods: {
    observeElements() {
      const observer = new IntersectionObserver(
        (entries) => {
          entries.forEach((entry) => {
            if (entry.isIntersecting) {
              entry.target.classList.add("animation");
            }
          });
        },
        { threshold: 0.2 }
      );

      const boxes = document.querySelectorAll(".box3, .box4");
      boxes.forEach((box) => observer.observe(box));
    },
  },
};
</script>

<style>
@import "../assets/css/detailsections.css";
</style>
