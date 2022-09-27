<template>
  <section>
    <base-card >
       <h2>FRUITS LIST</h2>

     <template v-slot:personal>
      <ul>
        <li>Apple</li>
        <li>Mango</li>
        <li>Lichi</li>
      </ul>
     </template>
      <!-- <template v-slot:personal>
         <h2>Fruits were Delicious</h2>
      </template> -->
    </base-card>
  </section>
</template>

<script>
export default {

}
</script>

<style>

</style>