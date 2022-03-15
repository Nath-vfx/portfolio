<template>
<form>
  <div>
    <div>
      <label for="surname">Votre prénom</label>
      <input type="text" id="surname" name="surname" required>
    </div>
    <div>
      <label for="name">Votre nom</label>
      <input type="text" id="name" name="name" required>
    </div>
    <div>
      <label for="email">Votre e-mail</label>
      <input type="text" id="email" name="email" required>
    </div>
  </div>

</form>
</template>

<script>
export default {
  name: "form"
}
</script>

<style scoped>

</style>
