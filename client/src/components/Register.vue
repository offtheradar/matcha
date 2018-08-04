<template>
  <div>
    <h1>Register</h1>
    <input
      type="email"
      name="email"
      v-model="email"
      placeholder="email" />
      <br>
       <input
      type="password"
      name="password"
      v-model="passowrd"
      placeholder="password" />
      <br>
       <input
      type="text"
      name="first_name"
      v-model="passowrd"
      placeholder="first name" />
      <br>
      <input
      type="text"
      name="last_name"
      v-model="last_name"
      placeholder="last name" />
      <br>
      <select name="gender">
        <option value="man">Man</option>
        <option value="woman">Woman</option>
      </select>
      <br>
        <select name="preference">
        <option value="man">Man</option>
        <option value="woman">Woman</option>
        <option value="woman">All</option>
      </select>
      <br>
      <button>Register</button>
  </div>
</template>

<script>
export default {
  data() {
    return {
    };
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
