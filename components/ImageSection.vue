<template>
  <div class="title__section" style="margin-bottom: 40px">
      <div class="title__backdrop">
      </div>
      <h1 class="title__name">Кафедра Будівництва, міського господарства та архітектури</h1>
  </div>
</template>

<script>
export default {
  name: "image-section"
}
</script>

<style scoped>
    .title__section {
        margin-top: 68px;
        position: relative;
        width: 100%;
        height: 400px;
        background-repeat: no-repeat;
        background-size: cover;
        background-image: url("assets/vntu-title.jpeg");
    }

    .title__backdrop {
        position: absolute;
        width: 100%;
        height: 100%;
        background-color: black;
        opacity: 0.4;
    }

    .title__name {
        width: 90%;
        position: absolute;
        left: 50%;
        transform: translate(-50%, 0);
        top: 50%;
        color: white;
        font-size: 2.5em;
        font-weight: bold;
        font-family: Helvetica;
    }
</style>
