<template>
  <div class="dropdown">
    <select v-model="selectedCity" @change="updateCity">
      <option value="Cidades" selected>Cidades</option>
      <option value="Paraty">Paraty</option>
      <option value="Campos">Campos do Jordão</option>
      <option value="Gramado">Gramado</option>
    </select>
  </div>
</template>

<script>
export default {
  data() {
    return {
      selectedCity: "Cidades", // Cidade inicial nula
    };
  },
  methods: {
    updateCity() {
      this.$emit("city-selected", this.selectedCity);
    },
  },
};
</script>

<style>
.dropdown select {
  background-color: inherit;
  color: #ccc;
  padding: 10px;
  font-size: 28px;
  margin: 10px auto;
  display: block;
  border: none;
  cursor: pointer;
}
.dropdown select option {
  font-size: 16px;
}
</style>
