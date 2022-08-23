<script setup>
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
import SupportIcon from './icons/IconSupport.vue'
</script>

<template>
<!-- <div class="more">
    <div class="job">
      <h3>Design for</h3>
      <h2>Website</h2>
    </div>

    <div class="phone">
      <h3>Phone</h3>
      <h2>+62 812-1351-7803</h2>
    </div>

    <div class="email">
      <h3>Drop your message</h3>
      <h2>@baguswicaksana217@gmail.com</h2>
    </div>

    <div class="address">
      <h3>Addres</h3>
      <img src="@/assets/Location.png" alt="" width="100" height="100">
    </div>
  </div> -->
    <div class="aboutme">
      <h1 class="fw-bold">About me</h1>
      <div class="bgp">
        <p>"Saya Bagus wicaksana, siswa di SMK Taruna Bhakti, jurusan Rekayasa Perangkat Lunak. Saya sangat tertarik pada bagian Front-end Developer, seperti User Interface Design"</p>
      </div>
    </div>
  
</template>

<style scoped>
.aboutme{
  height: 500px;
  background-color: white;
  width: 100%;
  padding-top: 30px;
}
.bgp{
  margin-top: 30px;
  width: 50%;
  height: 300px;
  border-radius: 0 50px 50px 0;
  background-color: rgba(242, 241, 239, 1);
}

.bgp p{
  padding: 30px 20px 0 20px;
  font-size: 20px;
  line-height: 35px;
}

.aboutme h1{
  text-align: center;
}

.more{
  display: flex;
  gap: 100px;
  margin: auto;
  margin-bottom: 150px;
  justify-content: center;
}

.more h2{
  font-size: 25px;
  font-weight: 400;
  padding-top: 5px;
}

.more h3{
  font-size: 20px;
}
</style>
