<template>
  <div class="wrapper">
    <div class="information">
      <div class="locationWrapper">
      <img src="./assets/icons/location.svg" class="iconLocation" />
      <span class="textLocation">Braga, Portugal</span>
      </div>
    </div>
    <div class="buttons">
      <div class="searchWrapper">
        <button class="searchBtn">
          <img src="./assets/icons/search.svg" />
        </button>
      </div>
    </div>
  </div>
</template>

<script setup>

</script>

<style scoped>
.wrapper{
  width: 23rem;
  height: 27rem;
  background-color: white;
  border-radius: 8%;
  display: flex;
  flex-direction: row;
  flex-wrap: nowrap;
  order:5;
}

.locationWrapper{
  padding: 10px;
  display: flex;
  align-items: center;
  gap: 20px;
}

.iconLocation{
  width: 1.5rem;
  height: 1.5rem;
}

.textLocation{
  font-size: large;
}

.textLocation:hover{
  font-style: italic;
}

.buttons{
  display: flex;
  justify-content: end;
}
</style>
