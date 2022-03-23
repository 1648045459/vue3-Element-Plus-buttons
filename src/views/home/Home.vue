<template>
  <CPage>
    <template #header> <CHeader /> </template>
    <div class="text-center">
      <h2>{{ t('title') }}</h2>
      <i-ep-add-location />
      <el-button :type="typeBtn">sfsdfsdf</el-button>
    </div>
  </CPage>
</template>
<script lang="ts" setup>
const { t } = useI18n({
  inheritLocale: true
});

const typeBtn = ref('info');
</script>
