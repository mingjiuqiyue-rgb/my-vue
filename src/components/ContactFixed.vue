<template>
  <div class="contact-fixed">
    <div
      class="contact-item wechat"
      @mouseenter="showQrCode = true"
      @mouseleave="showQrCode = false"
    >
      <img src="../assets/images/wechat_logo_icon_147207.webp" alt="微信" />
      <div class="qrcode" v-show="showQrCode">
        <img src="../assets/images/wcCode-UTQIXIC0.jpg" alt="微信二维码" />
      </div>
    </div>
    <a href="http://t.me/ZJDF007" target="_blank" class="contact-item telegram">
      <img
        src="../assets/images/telegram_logo_icon_168692.webp"
        alt="Telegram"
      />
    </a>
    <a
      href="http://wa.me/13554619576"
      target="_blank"
      class="contact-item whatsapp"
    >
      <img
        src="../assets/images/whatsapp_logo_icon_147205.webp"
        alt="WhatsApp"
      />
    </a>
  </div>
</template>

<script>
export default {
  name: "ContactFixed",
  data() {
    return {
      showQrCode: false,
    };
  },
};
</script>

<style>
@import "../assets/css/contactfixed.css";
</style>
