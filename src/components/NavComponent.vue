<template>
  <div>
    <nav class="navbar navbar-expand-lg navbar-light b">
      <div class="container-fluid">
        <a class="navbar-brand" href="#">
          <img
            class="fb-logo"
            src="https://cdn-icons-png.flaticon.com/512/5968/5968764.png"
            alt=""
          />
        </a>
        <form class="d-flex">
          <font-awesome-icon icon="fa-solid fa-magnifying-glass" />
          <input
            class="form-control fontAwesome"
            type="search"
            placeholder="  Search Facebook"
            aria-label="Search"
          />
        </form>
        <button
          class="navbar-toggler"
          type="button"
          data-bs-toggle="collapse"
          data-bs-target="#navbarSupportedContent"
          aria-controls="navbarSupportedContent"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <ul class="navbar-nav ms-auto me-auto mb-2 mb-lg-0">
            <li class="nav-item">
              <a class="nav-link active" aria-current="page" href="#">
                <i class="fa-solid fa-house"></i>
              </a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">
                <i class="fa-solid fa-tv"></i>
              </a>
            </li>
            <li class="nav-item">
              <a href="" class="nav-link">
                <i class="fa-solid fa-store"></i>
              </a>
            </li>
            <li class="nav-item">
              <a class="nav-link">
                <i class="fa-solid fa-users-line"></i>
              </a>
            </li>
            <li class="nav-item">
              <a href="" class="nav-link">
                <i class="fa-solid fa-dice-d20"></i>
              </a>
            </li>
          </ul>
        </div>
        <div class="right-menu">
          <div class="icon-bg">
            <a href="" class="dont-menu">
              <i class="fa-solid fa-bars"></i>
            </a>
          </div>
          <div class="icon-bg">
            <a href="" class="mess">
              <i class="fa-brands fa-facebook-messenger"></i>
            </a>
          </div>
          <div class="icon-bg">
            <a href="" class="notify">
              <i class="fa-solid fa-bell"></i>
            </a>
          </div>
          <img
            src="https://scontent.fbir1-1.fna.fbcdn.net/v/t39.30808-6/223223926_489625255672177_237755659900963056_n.jpg?_nc_cat=106&ccb=1-7&_nc_sid=09cbfe&_nc_ohc=ly557IrVC9kAX-Lx3OW&_nc_ht=scontent.fbir1-1.fna&oh=00_AT9JOx_nZQGgFKOTLyB87iGBfGmU4mMY9bB9RKduNfGs2Q&oe=630A1AF8"
            class="profile"
            alt=""
          />
        </div>
      </div>
    </nav>
    <div class="line"></div>
  </div>
</template>

<script>
export default {
    name: 'NavComponent'
};
</script>

<style scoped>
.fb-logo{
    width: 40px;
}
nav{
    background-color: #252527 !important;
    padding: 0 1%;

}
.navbar-nav{
    position: relative;
    left: -3%;
    display: flex;
    justify-content: space-between;
    /* background-color: red; */
    width: 35vw;
}
.nav-link{
    color: #6A6C6F!important;
    font-size: 22px !important;
    margin: 0 10px;
}
.fontAwesome{
    border-radius: 20px;
    background-color: #3B3B3D;
    border: none;
    color: #c4c8cb !important;
    height: 40px;
    width: 15vw !important;
}
::placeholder{
    color: #ABAFB2 !important;
}
i{
    color: white !important;
    background-color: white !important;
}
.dont-menu{
    font-size: 20px;
    color:  white;
    border-radius: 50%;
}
.mess{
    font-size: 20px;
    color: white;
    border-radius: 50%;
    background-color: #3B3B3D;
}
.notify{
     font-size: 20px;
    color: white;
    border-radius: 50%;
    background-color: #3B3B3D;
}
.profile{
    width: 40px;
    height: 40px;
    border-radius: 50%;
    object-fit: cover;
}
.right-menu{
    display: flex;
    justify-content: space-between;
    width: 13vw;
    /* background-color: blue; */
}
.icon-bg{
    /* background-color: red;
     */
    background-color: #3B3B3D;
    border-radius: 50%;
    width: 40px;
    display: flex;
    justify-content: center;
    align-items: center;
}
.line{
  width: 100vw;
  background-color: #383B3B;
  height: 1px;
}
</style>