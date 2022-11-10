<template>
  <Navbar />

  <div class="d-flex">
    <div class="col-4"><EntryList/></div>
    <div class="col"><router-view /></div>
  </div>
</template>

<script setup>
import Navbar from '../components/Navbar.vue'
import EntryList from '@/modules/daybook/components/EntryList.vue'



</script>
