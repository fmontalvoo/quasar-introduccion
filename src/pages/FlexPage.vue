<template>
  <q-page>

    <div class="row q-mb-sm">
      <div class="col bg-primary"></div>
      <div class="col bg-secondary"></div>
      <div class="col bg-accent"></div>
    </div>

    <div class="row q-mb-sm">
      <div class="col-5 bg-primary"></div>
      <div class="col-6 bg-secondary"></div>
      <div class="col bg-accent"></div>
    </div>

    <div class="row q-mb-sm justify-center">
      <div class="col-4 bg-primary"></div>
      <div class="col-4 bg-secondary"></div>
    </div>

    <div class="row q-mb-sm justify-between">
      <div class="col-4 bg-primary"></div>
      <div class="col-4 bg-secondary"></div>
    </div>

    <div class="row q-mb-sm justify-center">
      <div class="col-4 bg-accent"></div>
    </div>

    <q-separator spaced />

    <div class="row q-mb-sm justify-between">
      <div class="col-12 col-sm-4 col-md-6 bg-primary"></div>
      <div class="col-12 col-sm-4 col-md-6 bg-accent"></div>
    </div>

    <q-separator spaced />

    <div class="row">
      <div class="square-box bg-primary"></div>
      <div class="square-box bg-secondary"></div>
      <div class="square-box bg-accent"></div>
    </div>

    <q-separator spaced />

    <div class="row justify-between">
      <div class="square-box bg-primary"></div>
      <div class="square-box bg-secondary"></div>
      <div class="square-box bg-accent"></div>
    </div>

    <q-separator spaced />

    <div class="row justify-around">
      <div class="square-box bg-primary"></div>
      <div class="square-box bg-secondary"></div>
      <div class="square-box bg-accent"></div>
    </div>

    <q-separator spaced />

    <div class="row justify-end">
      <div class="square-box bg-primary"></div>
      <div class="square-box bg-secondary"></div>
      <div class="square-box bg-accent"></div>
    </div>

    <q-separator spaced />

    <div class="column items-start bg-dark">
      <div class="square-box bg-primary"></div>
      <div class="square-box bg-secondary"></div>
      <div class="square-box bg-accent"></div>
    </div>

    <q-separator spaced />

    <div class="column items-center bg-dark">
      <div class="square-box bg-primary"></div>
      <div class="square-box bg-secondary"></div>
      <div class="square-box bg-accent"></div>
    </div>

    <q-separator spaced />

    <div class="column items-end bg-dark">
      <div class="square-box bg-primary"></div>
      <div class="square-box bg-secondary"></div>
      <div class="square-box bg-accent"></div>
    </div>

    <q-separator spaced />

    <div class="column custom-height items-center justify-center bg-dark">
      <div class="square-box bg-primary"></div>
      <div class="square-box bg-secondary"></div>
      <div class="square-box bg-accent"></div>
    </div>

    <q-separator spaced />

    <div class="column custom-height items-center justify-between bg-dark">
      <div class="square-box bg-primary"></div>
      <div class="square-box bg-secondary"></div>
      <div class="square-box bg-accent"></div>
    </div>

    <q-separator spaced />

    <div class="column custom-height items-center justify-between bg-dark">
      <div class="square-box self-start bg-primary"></div>
      <div class="square-box bg-secondary"></div>
      <div class="square-box self-end bg-accent"></div>
    </div>

  </q-page>
</template>

<script>
import { defineComponent } from 'vue'

export default defineComponent({
  name: 'FlexPage'
})
</script>

<style scoped>
.col,
.col-4,
.col-6,
.col-12 {
  height: 50px;
}

.square-box {
  width: 50px;
  height: 50px;
}

.custom-height {
  height: 300px;
}
</style>
