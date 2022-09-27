<template>
  <div>
    <!-- WRITE SOMETHING -->
    <slot></slot>
    <body class="body1">
        <slot name="personal"></slot>
        
    </body>
  </div>
</template>

<script>
export default {

}
</script>

<style scoped>
div{
    box-shadow: 0 3px 9px rgba(0, 0, 0, 0.3);
    border-radius: 10px;
    max-width: 30rem;
    background-color: black;
    color: whitesmoke
}
.body1{
    background-color: brown;
    color:aliceblue;
    border-radius: 25px;
}
</style>