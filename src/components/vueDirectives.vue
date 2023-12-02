<template>
  <div>
    <AnimalCard
      v-for="(item, index) in listOfAnimals"
      :key="index"
      v-bind:index="index"
      v-bind:nickName="item.nickName"
      v-bind:[typeOfAnimalKey]="item.typeOfAnimal"
    />
  </div>
</template>

<script>
import AnimalCard from "./animalCard.vue";
export default {
  Components: { AnimalCard },
  data() {
    return {
      typeOfAnimalKey: "typeOfAnimal",

      listOfAnimals: {
        1: { nickName: "bimgo", typeOfAnimal: "dog" },
        2: { nickName: "clarias", typeOfAnimal: "fish" },
        3: { nickName: "cletuse", typeOfAnimal: "cat" },
      },
    };
  },
};
</script>

<style scoped></style>
