<script setup>
import WelcomeItem from "./WelcomeItem.vue";
import DocumentationIcon from "./icons/IconDocumentation.vue";
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from "./icons/IconEcosystem.vue";
import CommunityIcon from './icons/IconCommunity.vue'
import SupportIcon from "./icons/IconSupport.vue";
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <SupportIcon/>
    </template>
    <template #heading>Lưu ý</template>
    <text>Lưu ý: Đổi tên trước khi nộp theo định dạng &lt;tên&gt;.vrblocks hoặc &lt;tên1&gt;,&lt;tên2&gt;,&lt;tên3&gt;.vrblocks</text>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>Cách nộp bài</template>
    
    <div>Nộp bài qua <a
      href="https://classroom.google.com/c/NTczNDA4MDk4ODcy?cjc=5wd7u2z"
      target="_blank"
      rel="noopener"
      >Google Classroom</a
    >.</div>
    <text>
      <a
        href="https://classroom.google.com/c/NTczNDA4MDk4ODcy?cjc=5wd7u2z"
      target="_blank"
      rel="noopener"
      >Video hướng dẫn</a
    > 
    </text>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>Documentation</template>
      
  </WelcomeItem>
</template>
