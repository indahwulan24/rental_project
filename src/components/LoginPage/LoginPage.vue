<template>
  <div class="bac">
    <main class="form-signin grid place-items-center h-screen">
      <div class="border p-[30px]" >
      <form @submit.prevent="submit">
        <h1 class="text-center font-bold border-b-2 border-b-blue-600 pb-2 mb-3">LOGIN</h1>

        <div class="form-floating">
          <label class="text-red-700 font-bold">username</label>
          <input type="text"
          class="form-control border-b-2 border-b-blue-600"
          placeholder="username"/>
        </div>
        <div class="form-floating">
          <label class="text-red-700 font-bold">password </label>
          <input type="password"
            class="form-control border-b-2 border-b-blue-600"
            placeholder="password"/>
        </div>

        <button class="bg-sky-600 p-[10px] font-bold text-white w-full mt-3" type="submit">
          Login
        </button>

      </form>
      </div>
    </main>

  </div>
</template>

<script>
export default {
  name: 'LoginPage',
  components: {

  }
};
</script>

<style>
html,
body {
  height: 100%;
}

.text-center font-bold {
  font-size: xx-large;
}

.form-signin {
  width: 100%;
  max-width: 330px;
  padding: 15px;
  margin: auto;
}

.form-signin input[type="text"] {
  margin-bottom: 10px;
  border-top-left-radius: 0;
  border-top-right-radius: 0;
}

.form-signin input[type="password"] {
  margin-bottom: 10px;
  border-top-left-radius: 0;
  border-top-right-radius: 0;
}


@media (min-width: 768px) {
  
}
</style>
