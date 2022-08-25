<template>
  <div>
    <nav-component />
    <div class="row">
      <left-bar />
      <div class="col-md-6 main-section py-4">
        <!-- Story Section -->
        <div class="d-flex">
          <div class="my-story">
            <img
              src="https://scontent.fktm12-1.fna.fbcdn.net/v/t39.30808-6/223223926_489625255672177_237755659900963056_n.jpg?_nc_cat=106&ccb=1-7&_nc_sid=09cbfe&_nc_ohc=ly557IrVC9kAX-17SPL&_nc_ht=scontent.fktm12-1.fna&oh=00_AT824OI-jZ_sQhudYxyzITvLzKH5Ij8D0rAlWdAE0WR_7g&oe=630C1538"
              alt=""
              class="my-story-image"
            />
            <div class="add-story">
              <a href="" class="add-story-btn">
                <i class="fa-solid fa-circle-plus"></i>
              </a>
            </div>
            <div class="d-flex justify-content-center mt-4">
              <p class="story-name">Create story</p>
            </div>
          </div>
          <story-comp
            :profilePic="`https://scontent.fktm12-1.fna.fbcdn.net/v/t1.6435-9/145143874_1062578930903927_6526828013676758269_n.jpg?_nc_cat=102&ccb=1-7&_nc_sid=174925&_nc_ohc=gbCgVcR5Yk4AX_Fj8wC&_nc_ht=scontent.fktm12-1.fna&oh=00_AT9yrTHcXpMJS6sC44bc9Zc8Ia_Fcwt_My_VnSGl60dZ4g&oe=632D2924`"
            :storyImage="`https://scontent.fktm12-1.fna.fbcdn.net/v/t39.30808-6/301044936_10160533447968598_7839891348827855299_n.jpg?stp=dst-jpg_s960x960&_nc_cat=102&ccb=1-7&_nc_sid=730e14&_nc_ohc=qAvrI753dxIAX8ZQ29T&_nc_ht=scontent.fktm12-1.fna&oh=00_AT_TWH3K2XNYCB5HcR_lserWG9k2X5w-fMHRZYpwUpC6rw&oe=630C1794`"
            :name="`Niskarsh Shrestha`"
          />
          <story-comp
            :name="`Nijal Tamang`"
            :profilePic="`https://scontent.fktm12-1.fna.fbcdn.net/v/t1.6435-9/90717180_2763562613754800_6694257051134066688_n.jpg?stp=dst-jpg_p640x640&_nc_cat=110&ccb=1-7&_nc_sid=19026a&_nc_ohc=FwSHnLSd_X0AX938Ork&_nc_ht=scontent.fktm12-1.fna&oh=00_AT_yQk8iEZo1rjCWNcp2Y9mGtXmI42dfM7Sq0TDOxhrv4A&oe=632E7DE2`"
            :storyImage="`https://scontent.fktm12-1.fna.fbcdn.net/v/t31.18172-8/22181315_1381437265300682_7376945494202803807_o.jpg?stp=dst-jpg_p552x414&_nc_cat=107&ccb=1-7&_nc_sid=19026a&_nc_ohc=fqT87Dp5dcwAX9zt9mM&_nc_ht=scontent.fktm12-1.fna&oh=00_AT_dC9s7GkU74jA7O9ZYle-EEBZn6bbI0iXrcIadl8DgYQ&oe=632E8227`"
          />
          <story-comp
            :name="`Bijay Rai`"
            :profilePic="`https://scontent.fktm12-1.fna.fbcdn.net/v/t31.18172-1/13691090_1188879834498200_2633120180752328346_o.jpg?stp=dst-jpg_p320x320&_nc_cat=111&ccb=1-7&_nc_sid=7206a8&_nc_ohc=J0wVg9nOwJwAX-TWwaA&_nc_ht=scontent.fktm12-1.fna&oh=00_AT_essZiT01cRiCw6YugWCsc44g166sRmIppE_gPNomFmw&oe=632C79B1`"
            :storyImage="`https://scontent.fktm12-1.fna.fbcdn.net/v/t1.6435-9/65319529_2449785415074296_6855104757485273088_n.jpg?_nc_cat=105&ccb=1-7&_nc_sid=8bfeb9&_nc_ohc=sOtQpMonFygAX-nKSOi&_nc_ht=scontent.fktm12-1.fna&oh=00_AT-XvYl1J-DkIeO65nwM5n_0r-B1aEGM9emHTJyPCLlRpw&oe=632D2345`"
          />
          <story-comp
            :name="`Roh Hann`"
            :profilePic="`https://scontent.fktm12-1.fna.fbcdn.net/v/t39.30808-1/255334260_1252230451957947_8721847696695125402_n.jpg?stp=dst-jpg_p320x320&_nc_cat=102&ccb=1-7&_nc_sid=7206a8&_nc_ohc=N1AT9cUGsS8AX-IHeZz&_nc_ht=scontent.fktm12-1.fna&oh=00_AT8sH_Q6DwtSiSzyKQN2H2Kv02NBM_kNQy-3iAw_8GpC0w&oe=630B6C1E`"
            :storyImage="`https://scontent.fktm12-1.fna.fbcdn.net/v/t1.6435-9/173181329_1106870093160651_1784522011954410258_n.jpg?stp=dst-jpg_p640x640&_nc_cat=111&ccb=1-7&_nc_sid=174925&_nc_ohc=DhrqT7HYjvUAX8qUU2x&_nc_ht=scontent.fktm12-1.fna&oh=00_AT9JzQt-8CsxJ6UvFM8HMAVPpANXhInCoR9lpPXk0CvrkQ&oe=632E33E5`"
          />
        </div>
        <!-- Story Section Ends -->
        <!-- Status Bar -->
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
        <!-- Status Bar Ends -->
      </div>

      <right-bar />
    </div>
  </div>
</template>

<script>
import NavComponent from "@/components/NavComponent.vue";
import LeftBar from "@/components/LeftBar.vue";
import RightBar from "@/components/RightBar.vue";
import StoryComp from "@/components/StoryComp.vue";
export default {
  name: "TemplateView",
  components: { NavComponent, LeftBar, RightBar, StoryComp },
};
</script>

<style>
.main-section {
  height: 100vh;
  width: 39vw;
  /* background-color: red; */
  position: relative;
  left: 31%;
}
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
.my-story {
  width: 124px;
  height: 200px;
  background-color: #242526;
  border-radius: 12px;
  overflow: hidden;
}
.my-story-image {
  width: 100%;
  height: 150px;
  object-fit: cover;
}
.story-name {
  color: white !important;

  font-size: 12px;
  font-weight: 500;
  position: relative;
  top: -42px;
}
.add-story {
  background-color: #242526;
  border-radius: 20px;
  width: 43px;
  display: flex;
  justify-content: center;
  align-items: center;
  height: 45px;
  position: relative;
  left: 30%;
  top: -10%;
}
.add-story-btn {
  color: #2e89ff;
  /* background-color: white; */
  font-size: 34px;
  /* border-radius: 50%; */
}

body::-webkit-scrollbar {
  width: 17px !important;
  /* display: none !important; */
}
body::-webkit-scrollbar-track {
  /* box-shadow: i0 0 0 ;
  border-radius: 10px !important; */
}
body::-webkit-scrollbar-thumb {
  background: #747979;
  /* border-radius: 10px; */
}
body:hover {
  overflow-y: scroll !important;
}
</style>