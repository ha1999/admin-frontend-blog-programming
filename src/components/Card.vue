<template>
  <vs-card-group>
    <vs-card v-for="card in 10" @click="handleClick" :key="card">
      <template #title>
        <h3>Pot with a plant</h3>
      </template>
      <template #img>
        <img :src="`https://vuesax.com/foto${card}.png`" alt />
      </template>
      <template #text>
        <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit.</p>
      </template>
      <template #interactions>
        <vs-button danger icon>
          <i class="bx bx-heart"></i>
          <span class="span">54</span>
        </vs-button>
        <vs-button class="btn-chat" shadow primary>
          <i class="bx bx-chat"></i>
          <span class="span">54</span>
        </vs-button>
      </template>
      <template #buttons>
        <vs-button class="btn-chat" shadow primary>
          <i class="bx bx-chat"></i>
          <span class="span">54</span>
        </vs-button>
      </template>
    </vs-card>
  </vs-card-group>

</template>

<script>
export default {
  name: "Card",
};
</script>