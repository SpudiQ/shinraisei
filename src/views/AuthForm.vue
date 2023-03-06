<template>
  <div class="container">
    <div class="AuthForm">
      <div class="AuthForm__container">
        <div class="AuthForm__btns">
          <button>Login</button>/
          <button>Register</button>
        </div>

        <form action="" @submit.prevent="onLogin" name="Login">
          <input type="text" name="email" class="email" autocomplete="off"/>
          <input type="password" class="password" />
          <button>Login</button>
        </form>
        <form action="" @submit.prevent="onRegister">
          <input type="text" class="username" />
          <input type="text" class="email" />
          <input type="password" class="password" />
          <button>Register</button>
        </form>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  data() {
    return {

    }
  },
  methods: {
    onClick() {
      console.log("Clicked");
    },
  },
};
</script>
<style scoped>
form {
  display: flex;
  flex-direction: column;
}

.container {
  display: grid;
  place-content: center;
  min-height: 80vh;
}

.AuthForm {
  min-height: 30vh;
  width: 45vh;
  background-color: rgba(255, 255, 255, 0.05);
  border-radius: 20px;
}

.AuthForm__container {
  padding: 25px 10%;
}

.AuthForm__btns {
    padding: 25px
}

input {
  color: white;
  font-size: 24px;
  margin: 2% 0;
  padding: 3% 0 3% 60px;

  border: 2px solid #ffffff;
  border-radius: 20px;
}

.username {
  background: url("@/assets/icons/AuthUsername.png") no-repeat scroll 2%;
}

.email {
  background: url("@/assets/icons/AuthEmail.png") no-repeat scroll 2%;
}

.password {
  background: url("@/assets/icons/AuthPassword.png") no-repeat scroll 2%;
}
</style>