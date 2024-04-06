<script setup>
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
import SupportIcon from './icons/IconSupport.vue'
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading style="color: orange;">Pendidikan</template>
    <P style="color: orange;">2008-2014</P>
    <p style="color: black;" > <a href="https://uir.ac.id/" target="_blank" rel="noopener">SD Negri 1 Pekanbaru</a> </p>
    <P style="color: orange;">2018-2021</P>
    <p style="color: black;" > <a href="https://www.isl.ch/fr/?utm_source=google&utm_medium=cpc&utm_campaign=g&utm_content=627678336171&utm_term=institut%20le%20rosey&hsa_acc=2016604778&hsa_cam=18575915412&hsa_grp=146015037007&hsa_ad=627678336171&hsa_src=g&hsa_tgt=kwd-463734713655&hsa_kw=institut%20le%20rosey&hsa_mt=p&hsa_net=adwords&hsa_ver=3&gad_source=1&gclid=CjwKCAjw_LOwBhBFEiwAmSEQAVoPXeWtbJR5OGmI0oBb-WX00bEhBJeGjnAgu80eMTBfIaOib70wdRoCr-gQAvD_BwE" target="_blank" rel="noopener">Institut Le Rosey (SMP)</a> </p>
    <P style="color: orange;">2018-2021</P>
    <p style="color: black;" > <a href="https://smkn1pekanbaru.sch.id/" target="_blank" rel="noopener">SMK Negri 1 Pekanbaru</a> </p>
    <P style="color: orange;">2022-NOW</P>
    <p style="color: black;" > <a href="https://uir.ac.id/" target="_blank" rel="noopener">UNIVERSITAS ISLAM RIAU</a> </p>
    
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Tentang Saya </template>

    
    <p class="centered-text" style="color: rgb(255, 255, 255);"> Saya adalah seorang <a href="https://www.google.com/search?q=jual+motor+bekas+pekanbaru&oq=jual+motor&gs_lcrp=EgZjaHJvbWUqBwgAEAAYgAQyBwgAEAAYgAQyCQgBEEUYORiABDIKCAIQABixAxiABDIHCAMQABiABDIHCAQQABiABDIHCAUQABiABDIHCAYQABiABDIHCAcQABiABDIHCAgQABiABDIHCAkQABiABNIBCDIxNzhqMGoxqAIAsAIA&sourceid=chrome&ie=UTF-8" target="_blank" rel="noopener">entrepreneur</a>, yang percaya pada kekuatan kreativitas, ketekunan, dan kolaborasi. Saya selalu mencari tantangan baru dan senang berbagi  <a href="" target="_blank" rel="noopener">Pengetahuan</a>, dengan orang lain. Komitmen saya adalah untuk terus belajar dan menginspirasi orang lain dalam mencapai  <a href="" target="_blank" rel="noopener">kesuksesan dalam bisnis dan kehidupan</a>,</p>
    
    
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Hobi</template>

    <p style="color: white;">Saya seorang pengusaha yang bersemangat dengan bisnis dan biliar.</p>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Specialist In </template>
    <p style="color: white;">
      Specialist entrepreneurs are analytical and avoid risks, have a strong skill set in a specific area obtained through education or apprenticeship
    </p>
          
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Support Me</template>

   <p style="color: white; text-align: justify;">Support me bukan hanya tentang memberikan dukungan finansial, tetapi juga tentang memberikan dorongan moral dan semangat. Dengan dukunganmu, aku merasa lebih kuat dan yakin dalam mengejar impian dan tujuan hidupku. Terima kasih karena selalu ada di sampingku, memberikan dukungan tanpa syarat. Bersama, kita bisa mencapai hal-hal luar biasa.</p> 
  </WelcomeItem>
</template>

<style scoped>
/* Untuk mengubah warna teks menjadi hitam */
p, code {
  color: black;
}
.centered-text {
    color: white;
    text-align: justify;
  }
</style>
