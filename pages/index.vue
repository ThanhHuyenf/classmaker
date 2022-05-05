<template>
    <iframe src="https://www.classmarker.com/online-test/start/?quiz=xn662729a78d790d&iframe=1" frameborder="0"
            style="width:100%;max-width:700px;" height="800"></iframe>
</template>
<script>
export default {
  data: () => ({
    selectedItem: 0,
    items: [
      {text: 'My Files', icon: 'mdi-folder'},
      {text: 'Shared with me', icon: 'mdi-account-multiple'},
      {text: 'Starred', icon: 'mdi-star'},
      {text: 'Recent', icon: 'mdi-history'},
      {text: 'Offline', icon: 'mdi-check-circle'},
      {text: 'Uploads', icon: 'mdi-upload'},
      {text: 'Backups', icon: 'mdi-cloud-upload'},
    ],
  }),
}
</script>

<!--<script lang="ts" setup>-->
<!--import DefaultLayout from '@/layouts/default.vue'-->
<!--export default {-->
<!--  components: {-->
<!--    DefaultLayout-->
<!--  },-->
<!--  data: () => ({-->
<!--    selectedItem: 0,-->
<!--    items: [-->
<!--      { text: 'My Files', icon: 'mdi-folder' },-->
<!--      { text: 'Shared with me', icon: 'mdi-account-multiple' },-->
<!--      { text: 'Starred', icon: 'mdi-star' },-->
<!--      { text: 'Recent', icon: 'mdi-history' },-->
<!--      { text: 'Offline', icon: 'mdi-check-circle' },-->
<!--      { text: 'Uploads', icon: 'mdi-upload' },-->
<!--      { text: 'Backups', icon: 'mdi-cloud-upload' },-->
<!--    ],-->
<!--  }),-->
<!--}-->
<!--</script>-->
