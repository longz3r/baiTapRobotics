<script setup>
import WelcomeItem from "./WelcomeItem.vue";
import DocumentationIcon from "./icons/IconDocumentation.vue";
import ToolingIcon from './icons/IconTooling.vue'
// import EcosystemIcon from "./icons/IconEcosystem.vue";
// import CommunityIcon from './icons/IconCommunity.vue'
import SupportIcon from "./icons/IconSupport.vue";
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <ToolingIcon/>
    </template>
    <template #heading>Lưu ý</template>
    <a href="https://vr.vex.com" target="_blank" >Chọn playground Art Canvas+ </a>
    <div></div>
    <text>Lưu ý: Đổi tên trước khi nộp theo định dạng &lt;tên&gt;.vrblocks hoặc &lt;tên1&gt;,&lt;tên2&gt;,&lt;tên3&gt;.vrblocks</text>
    <div>Căn giữa hình trên Cavas, màu tương tự trên hình vẽ có thể thay bằng màu khác</div>
    <div>Tam giác là tam giác đều (cạnh của tam giác và bán kính đường tròn tuỳ chỉnh)</div> 
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Cách nộp bài</template>
    
    <div>Nộp bài qua <a
      href="https://classroom.google.com/c/NTczNDA4MDk4ODcy?cjc=5wd7u2z"
      target="_blank"
      rel="noopener"
      >Google Classroom</a
    >.</div>
    <text>
      <iframe width="350" height="200" src="https://www.youtube.com/embed/wZ0fmJF6Evc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
    </text>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>Gợi ý</template>
      <div>Di chuyển đến góc của hình chữ nhật => vẽ hình chữ nhật (dùng vòng lặp nếu có thể)</div>
      <div>Chia dọc và chia ngang</div>
      <div>Di chuyển vào giũa từng hình và vẽ</div>
  </WelcomeItem>
</template>
