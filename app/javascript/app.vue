<template>
  <v-app>
    <div id="bg-img">
      <div id="content">
        <div id="catch-copy">
          <h1>Typing for programer</h1>
          <h2>with Tiepy</h2>
        </div>
        <div id="buttons">
          <div id="area">
            <div id="introduce"><v-btn color="primary" block rounded x-large>How to use</v-btn></div>
            <div id="login">
              <div id="sign-up"><v-btn color="teal lighten-1" rounded x-large dark>新規登録</v-btn></div>
              <div id="sign-in"><v-btn color="teal lighten-1" rounded x-large dark>ログイン</v-btn></div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </v-app>
</template>

<script>
export default {
  data: function () {
    return {
    }
  }
}
</script>

<style scoped>
#bg-img {
  background-image: url(../assets/images/student-849822.jpg);
  min-height: 100vh;
  background-size: cover;
  background-position: center top;
  background-repeat: no-repeat;
  display: flex;
  justify-content: center;
  align-items: center;
}

#content {
  height: 70%;
  width: 90%;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}

#catch-copy {
  /* background-image: url(../assets/images/4208448_m.png); */
  background-size: cover;
  background-position: center;
  background-color: antiquewhite;
  border-top-left-radius: 40px;
  border-top-right-radius: 40px;
  border-bottom-right-radius: 40px;
  border-bottom-left-radius: 40px;
  height: 40%;
  width: 60%;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;

}

h1 {
  font-size: 4rem;
  font-family: serif;
  text-align: center;
}

h2 {
  font-size: 2.5rem;
  font-family: serif;
}

#buttons {
  height: 40%;
  width: 100%;
  display: flex;
  justify-content: center;
  padding-top: 20px;
}

#area {
  height: 100%;
  width: 30%;
}

#login {
  height: 40%;
  width: 100%;
  display: flex;
  justify-content: space-between;
  padding-top: 40px;
}
</style>
