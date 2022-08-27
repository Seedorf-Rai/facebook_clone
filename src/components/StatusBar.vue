<template>
  <div class="status-box py-4 px-3">
          <div class="d-flex">
            <img
              src="https://scontent.fktm12-1.fna.fbcdn.net/v/t39.30808-6/223223926_489625255672177_237755659900963056_n.jpg?_nc_cat=106&ccb=1-7&_nc_sid=09cbfe&_nc_ohc=ly557IrVC9kAX-17SPL&_nc_ht=scontent.fktm12-1.fna&oh=00_AT824OI-jZ_sQhudYxyzITvLzKH5Ij8D0rAlWdAE0WR_7g&oe=630C1538"
              class="left-profile"
              alt=""
            />
            <input
              class="form-control fontAwesome ms-2"
              type="search"
              placeholder=" What's on your mind, See?"
              aria-label="Search"
            />
          </div>
          <div class="line2 my-3"></div>
          <div class="d-flex">
            <div class="status-icon">
              <a href="" class="icon-vid"><i class="fa-solid fa-video"></i></a>
              <p class="icon-name ms-3 mt-2">Live Video</p>
            </div>
            <div class="status-icon">
              <a href="" class="icon-img"><i class="fa-solid fa-images"></i></a>
              <p class="icon-name ms-3 mt-2">Photo/Video</p>
            </div>
            <div class="status-icon">
              <a href="" class="icon-smile"><i class="fa-regular fa-face-laugh-beam"></i></a>
              <p class="icon-name ms-3 mt-2">Feeling/Activity</p>
            </div>
          </div>
        </div>
</template>

<script>
export default {
  name: 'StatusBar'
}
</script>

<style>
.icon-vid{
  color: #F2425E;
  font-size: 27px;
}
.icon-img{
  font-size: 27px;
  color: #44BC62;
}
.icon-name{
  color: #aaadb1;
}
.icon-smile{
  color: #F6B929;
  font-size: 27px;
}
.status-icon{
  display: flex;
  /* background-color: blue; */
  width: 13vw;
  align-items: center;
  padding-left: 25px;
  border-radius: 8px;
}
.status-icon:hover{
  background-color: #3B3B3D;
  cursor: pointer;
}
.status-box {
  background-color: #242526;
  border-radius: 8px;
  margin-top: 23px;
}
.fontAwesome {
  border-radius: 20px;
  background-color: #3b3b3d;
  border: none;
  color: #c4c8cb !important;
  height: 40px;
  width: 34vw !important;
}

::placeholder {
  color: #abafb2 !important;
}


</style>