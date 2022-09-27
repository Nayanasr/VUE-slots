<template>
  <div>
    <base-card>
    <h2>NAME:{{ userData.name }}</h2>
    <p>{{ userData.description }}</p>
    <p>ROLE is:{{ userData.role }}</p>
     <template v-slot:personal>
        <h3>THIS SECTION IS PERSONAL: no one should read it....</h3>
    </template>
    </base-card>
  </div>
</template>

<script>
export default {
     props: ["userData"]
}
</script>

<style>

</style>