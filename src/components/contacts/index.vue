<script setup lang="ts">

import { MaskInput } from "vue-3-mask";
import Container from "../container/index.vue";
import { toast } from 'vue3-toastify';
import { ref } from "vue";
const phoneNumber = ref("");
const name = ref("");


const handleSubmit = () => {
    if(name.value.length > 0 && phoneNumber.value.length == 19){
        toast.success("Sizning so'rovingiz yuborildi")
    }
}

</script>

<template>
  <section id="contacts">
    <h2 class="contact-title">Contact Us</h2>
    <Container>
      <div class="contact-wrapper">
        <h2>Robototexnika kursiga qabul boshlangan !</h2>
        <h3>Hoziroq ro'yxatdan o'ting</h3>
        <p>va farzandingiz kelajagi uchun muhim qadamni tashlang</p>
        <div class="inputs">
          <input v-model="name" type="text" placeholder="Ismingiz" />
          <MaskInput v-model="phoneNumber" mask="+998-(##) ###-##-##" />
        </div>
        <button @click="() => handleSubmit()">Yuborish</button>
      </div>
    </Container>
  </section>
</template>

<style lang="scss" src="./style.scss" scoped></style>
