<template>
  <nav id="navbar">
    <div class="menu">
      <img src="@/assets/Logo.svg" alt="DevBank">

      <a href="#">Sobre nós</a>
      <a href="#">Para você</a>
      <a href="#">Para sua empresa</a>
      <a href="#">Suporte</a>
    </div>

    <div class="login">
      <a href="#" id="login-link">
        <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
          <path d="M12 2C9.243 2 7 4.243 7 7C7 9.757 9.243 12 12 12C14.757 12 17 9.757 17 7C17 4.243 14.757 2 12 2ZM12 10C10.346 10 9 8.654 9 7C9 5.346 10.346 4 12 4C13.654 4 15 5.346 15 7C15 8.654 13.654 10 12 10ZM21 21V20C21 16.141 17.859 13 14 13H10C6.14 13 3 16.141 3 20V21H5V20C5 17.243 7.243 15 10 15H14C16.757 15 19 17.243 19 20V21H21Z" fill="white" id="icon-login"/>
        </svg>
        Fazer login
      </a>
      <a href="#">Cadastrar-se</a>
    </div>
  </nav>
</template>

<script>
export default {

}
</script>

<style scoped>
  #navbar {
    height: 6.25rem;
    justify-content: space-between;
    padding: 0 5rem;
  }
  #navbar, .menu, .login, .login a {
    display: flex;
    align-items: center;
  }

  #navbar a{
    text-decoration: none;
  }

  .menu {
    gap: 2.0625rem;
  }

  .menu a, .login a {
    transition: 0.5s all ease;
    padding: .5rem 1.0625rem;
    border-radius: 1.25rem;
    color: #FFFFFF
  }

  .menu a:hover {
    background-color: #494949;
  }

  .login a svg #icon-login {
    transition: 0.5s all ease;
  }

  .login a:hover, .login a:hover svg #icon-login {
    background-color: #FFFFFF;
    color: #000000;
    fill: #000000;
  }

  .login {
    gap: 2.1875rem;
  }

  .login #login-link svg{
    margin-right: .625rem;
  }
</style>