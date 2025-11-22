<template>
  <div>
    <MyNavbar/>
  </div>

  <div class="flex flex-col md:flex-row items-center justify-center backGroundMain p-6 md:p-10 gap-6 lg:mt-40">


    <div class="flex shrink-0">
      <img
        class="rounded-full object-cover imgMain w-100"
        :src="iconMeuList"
        alt="Icona"
      />
    </div>


    <div class="flex flex-col text-center md:text-left lg:ml-10">
      <h1 class="text-3xl font-bold textTit roboto-slab">PROGETTO MEUCCI</h1>
      <h2 class="text-2xl font-bold textSub roboto-slab">"La scuola che vogliamo, la costruiamo insieme"</h2>
      <p class="text-xl  mt-2 textTit roboto-slab">
        La nostra lista si impegna a migliorare la scuola attraverso progetti concreti e inclusivi,
        <br>pensati per valorizzare ogni studente.
        <br>Vogliamo rendere l’ambiente scolastico più accogliente,
        <br>sicuro e stimolante, promuovendo attività che favoriscano collaborazione, partecipazione e benessere.
        <br>Il nostro obiettivo è costruire una comunità scolastica più moderna,
        <br>attenta alle esigenze di tutti e capace di offrire nuove opportunità di crescita.
      </p>
    </div>

  </div>
</template>

<script setup>
import iconMeuList from '@/assets/iconMeuList.png';
import MyNavbar from '@/components/MyNavbar.vue';
</script>


<style scoped>

.textTit{

  color: #042C54;
}

.textSub{
  color: #FFC787
}

</style>
