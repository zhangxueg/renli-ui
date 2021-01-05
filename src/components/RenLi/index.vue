<template>
  <div>
    <svg-icon icon-class="download" @click="handleDownload" />
  </div>
</template>

<script>
export default {
  name: "Renli",
  data() {
    return {
      url: "https://github.com/zhangxueg/renli-ui.git",
    };
  },
  methods: {
    handleDownload() {
      window.open(this.url);
    },
  },
};
</script>