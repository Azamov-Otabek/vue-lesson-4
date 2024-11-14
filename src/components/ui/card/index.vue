<script setup lang="ts">
import LogoCard from "../../../assets/images/juniors.png";
</script>

<template>
  <div class="card">
    <div class="bg-fon"></div>
    <img :src="LogoCard" alt="Card Img" />
    <div class="card-body">
      <h2>Frontend</h2>
      <p>
        Frontend development kursi pdp kids loyihasining yosh jihatidan uchinchi kursi
        hisoblanadi. Bu kursda o’quvchilar  web sahifalarning bizga ko'rinadigan vizual
        qismini yaratishadi.
      </p>
      <ul>
        <li>
            <h3>Davomiligi</h3>
            <span>10 oy</span>
        </li>
        <li>
            <h3>Yosh chegarasi</h3>
            <span>10 - 14</span>
        </li>
      </ul>
    </div>
  </div>
</template>

<style lang="scss" src="./style.scss" scoped></style>
