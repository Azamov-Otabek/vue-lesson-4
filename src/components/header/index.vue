<script setup lang="ts">
    import Container from '../container/index.vue'
    import Logo from '../../assets/images/logo.png'
    
</script>

<template>
  <header>
      <Container>
          <nav>
            <div class="nav-left">
                <img :src="Logo" alt="header logo">
                <ul>
                    <li><a href="#juniors">Kurslarimiz</a></li>
                    <li><a href="#contacts">Bog'lanish</a></li>
                </ul>
            </div>
            <div class="nav-right">    
                    <i class='bx bxs-phone'></i>
                    <span>(78) 777-47-47</span>
            </div>
          </nav>
      </Container>
  </header>
</template>

<style lang="scss" src="./style.scss" scoped></style>
