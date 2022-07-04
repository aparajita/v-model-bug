<template>
  <div id="container">
    <IonInput type="number" v-model="options.number" />
  </div>
</template>

<script setup lang="ts">
import { reactive } from 'vue'
import { IonInput } from '@ionic/vue'

const options = reactive({
  number: 0
})
</script>

<style scoped>
#container {
  text-align: center;
  position: absolute;
  left: 0;
  right: 0;
  top: 50%;
  transform: translateY(-50%);
}

#container strong {
  font-size: 20px;
  line-height: 26px;
}

#container p {
  font-size: 16px;
  line-height: 22px;
  color: #8c8c8c;
  margin: 0;
}

#container a {
  text-decoration: none;
}
</style>
