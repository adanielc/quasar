<template>
  <q-card>
    <q-card-section> Texto </q-card-section>
    <q-card-section> {{ model }} </q-card-section>
    <q-card-section>
      <div class="q-gutter-md row items-start">
        <q-date v-model="model" mask="YYYY-MM-DD HH:mm" color="purple" />
        <q-time v-model="model" mask="YYYY-MM-DD HH:mm" color="purple" />
      </div>
    </q-card-section>
    <q-card-actions><q-btn>Accept</q-btn></q-card-actions>
  </q-card>
</template>

<script>
export default {
  data() {
    return {
      model: "",
    };
  },
};
</script>

<style></style>
