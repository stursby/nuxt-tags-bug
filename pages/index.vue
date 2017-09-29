<template>
  <div>
    <form>
      <label for="name">Name</label>
      <input type="text" id="name">
      <label for="email">Email</label>
      <input type="email" id="email">
      <label for="address">Address</label>
      <input type="text" id="address">
    </form>
  </div>
</template>

<style>

body {
  padding: 30px;
  font-size: 1.2rem;
  font-family: sans-serif;
}

label,
input {
  display: block;
}

input {
  margin-bottom: 1rem;
  padding: 5px;
}

input[type=text] {
  background: lightgray;
  outline: none;
  border: none;
}

</style>
