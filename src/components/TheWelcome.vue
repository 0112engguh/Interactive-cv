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
  </div> -->
  <div class="aboutme">
    <h1 class="fw-bold">About me</h1>
    <div class="pleks">
      <div class="bgp">
        <p>"Saya Bagus wicaksana, siswa di SMK Taruna Bhakti, berusia 17 tahun, jurusan Rekayasa Perangkat Lunak. Saya sangat tertarik
          pada bagian Front-end Developer, seperti HTML, CSS dan User Interface Design"</p>
      </div>
      <div class="interest">
        <h3 class="mt-4 text-center">Main Interest</h3>
        <ul class="mt-4">
          <li>Photography</li>
          <li>Graphic Design</li>
          <li>User Interface Design for website</li>
          <li>Web Development</li>
        </ul>

        <h3 class="mt-5 mb-5 text-center">Drop your message</h3>
        <div class="phone d-flex flex-row mb-2 ">
          <img src="@/assets/phone.svg" alt="">
          <h4>+62 812-1351-7803</h4>
        </div>

        <div class="email d-flex flex-row mb-2">
          <img src="@/assets/email.svg" alt="">
          <h4>baguswicaksana217@gmail.com</h4>
        </div>
      </div>
    </div>
    
    <div class="maps">
      <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3965.1808791956914!2d106.85963001458961!3d-6.3706332953901175!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x2e69ec7d21d03ed7%3A0xdbb670e2ab584ef0!2sJl.%20Keranji%20No.16%2C%20Mekarsari%2C%20Kec.%20Cimanggis%2C%20Kota%20Depok%2C%20Jawa%20Barat%2016452!5e0!3m2!1sid!2sid!4v1661271953793!5m2!1sid!2sid" width="500" height="250" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>

      <h2>Here<br>i stay</h2>
    </div>
    

  </div>

</template>

<style scoped>
  h2{
    margin-left: 650px;
    top: -260px;
    font-size: 70px;
    line-height: 100px;
    font-weight: bold;
    color: hsla(160, 100%, 37%, 1);
  }

  iframe{
    margin-top: -1000px;
    margin-left: 60px;
  }
  .aboutme {
    height: 900px;
    background-color: white;
    width: 100%;
    padding-top: 30px;
  }

  .pleks {
    display: flex;
    gap: 20px;
    margin-bottom: -30px;
  }

  .bgp {
    margin-top: 30px;
    width: 70%;
    height: 300px;
    border-radius: 0 50px 50px 0;
    background-color: rgba(242, 241, 239, 1);
  }

  .bgp p {
    padding: 30px 20px 0 20px;
    font-size: 20px;
    line-height: 35px;
  }

  .interest {
    margin-top: 30px;
    width: 25%;
    height: 600px;
    border-radius: 50px;
    background-color: rgba(242, 241, 239, 1);
  }

  .interest li {
    font-size: 20px;
    margin-left: 15px;
  }

  .interest img{
    width: 30px;
    height: 30px;
    margin-left: 20px;
    margin-bottom: 15px;
  }

  .interest h4{
    font-size: 20px;
    margin-left: 15px;
  }

  .aboutme h1 {
    text-align: center;
  }

  /* .more{
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
} */
</style>