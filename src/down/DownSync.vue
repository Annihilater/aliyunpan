<script setup lang="ts">
const handleClick = () => {}
</script>

<template>
  <div style="height: 7px"></div>
  <div class="toppanbtns" style="height: 26px"></div>
  <div style="height: 14px"></div>
  <div class="toppanbtns" style="height: 26px">
    <div class="toppanbtn">
      <a-button type="text" size="small" tabindex="-1" @click="handleClick"><i class="fa-solid fa-play-circle" />新建任务</a-button>
      <a-button type="text" size="small" tabindex="-1" @click="handleClick"><i class="fa-solid fa-circle-pause" />暂停任务</a-button>
      <a-button type="text" size="small" tabindex="-1" @click="handleClick"><i class="fa-solid fa-trash" />删除任务</a-button>
    </div>

    <div v-if="false" class="toppanbtn">
      <a-button type="text" size="small" tabindex="-1" @click="handleClick"><i class="fa-solid fa-circle-pause" />修改设置</a-button>
      <a-button type="text" size="small" tabindex="-1" @click="handleClick"><i class="fa-solid fa-sync" />同步日志</a-button>
      <a-button type="text" size="small" tabindex="-1" @click="handleClick"><i class="fa-solid fa-play-circle" />立即同步</a-button>
    </div>
  </div>
  <div style="height: 9px"></div>
  <div class="toppanarea">
    <div class="cell pr"></div>
  </div>
  <div class="toppanlist" @keydown.space.prevent="() => true">文件同步功能--还没做</div>
</template>

<style></style>
