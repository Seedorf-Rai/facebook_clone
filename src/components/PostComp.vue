<template>
   <div class="post mb-2">
          <div class="post-head">
            <div class="d-flex post-profile-box py-2 px-4">
              <div class="post-profile d-flex">
                <img
                  :src="userPicture"
                  class="left-profile mt-2"
                  alt=""
                />
                <div class="profile-name ms-2">
                  <p class="p-1">{{ userName }}</p>
                  <p class="p-2">
                    {{ time }} <span> . </span>
                    <span><i class="fa-solid fa-earth-asia"></i></span>
                  </p>
                </div>
              </div>
              <a
                href=""
                class="ms-auto"
                style="color: #b0b3b8; font-size: 24px"
              >
                <i class="fa-solid fa-ellipsis"></i>
              </a>
            </div>
            <div class="caption px-4">
              <p class="caption-p">
                {{ caption }}
              </p>
            </div>
            <img
              :src="image"
              class="post-image"
              alt=""
            />
            <div class="reactions my-1 px-3 d-flex py-2">
              <div>
                <img
                  src="https://cdn-icons-png.flaticon.com/512/1182/1182670.png"
                  class="rect-icon icon1"
                  alt=""
                />
                <img
                  src="https://cdn-icons-png.flaticon.com/512/742/742752.png"
                  class="rect-icon icon2"
                  alt=""
                />
                <img
                  src="https://cdn-icons-png.flaticon.com/512/742/742797.png"
                  class="rect-icon icon3"
                  alt=""
                />
              </div>
              <div>
                <p class="rx-name ms-2">Anant Todi and 3.6K others</p>
              </div>
              <div class="ms-auto">
                <p class="rx-name">1.3K comments 3K shares</p>
              </div>
              <div></div>
            </div>
            <div class="px-3">
              <div class="line3"></div>
            </div>
            <div class="rxn-btn d-flex justify-content-between  px-4">
              <div class="d-flex btn-div">
                <a href="" class="like-btn">
                  <i class="fa-regular fa-thumbs-up"></i>
                </a>
                <p class="rxn-btn-name">Like</p>
              </div>
              <div class="d-flex btn-div">
                <a href="" class="cmnt-btn">
                  <i class="fa-regular fa-message"></i>
                </a>
                <p class="rxn-btn-name">Comment</p>
              </div>
              <div class="d-flex btn-div">
                <a href="" class="share-btn">
                  <i class="fa-solid fa-share"></i>
                </a>
                <p class="rxn-btn-name">Share</p>
              </div>
            </div>
            <div class="px-3">
              <div class="line4"></div>
            </div>
            <div class="d-flex px-3 pt-3">
                <img
                  src="https://scontent.fbir1-1.fna.fbcdn.net/v/t39.30808-6/223223926_489625255672177_237755659900963056_n.jpg?_nc_cat=106&ccb=1-7&_nc_sid=09cbfe&_nc_ohc=TBf6Rua-lVgAX-O26Hj&_nc_ht=scontent.fbir1-1.fna&oh=00_AT-JucMLKsDRBIaF9RW077fN9JUOAFD3u5NwBtlZGLta7A&oe=630E0F78"
                  class="left-profile mt-2"
                  alt=""
                />
                <input
              class="form-control fontAwesome ms-2 mt-2"
              type="search"
              placeholder="Write a comment..."
              aria-label="Search"
            />
            </div>
          </div>
        </div>
</template>

<script>
export default {
   name: 'PostComp',
   props: ['userPicture','userName','time','caption','image']
}
</script>

<style>
.like-btn,.cmnt-btn,.share-btn{
  color: #8E9396;
  font-size: 24px;
}
.rxn-btn-name{
  font-size: 19px;
  margin-top: 2px;
  margin-left: 15px;
  color: #8E9396;
  font-weight: 600;
}
.btn-div{
  width: 100%;
  padding-left: 20px ;
}
.btn-div:hover{
  background-color: #3B3B3D;
  border-radius: 10px;
  cursor: pointer;
}
.rxn-btn {
  width: 100%;
  height: 40px;
  /* background-color: red; */
  margin-top: 10px;
}
.post {
  width: 100%;
  height: 800px;
  background-color: #252527;
  margin-top: 20px;
  border-radius: 10px;
  margin-bottom: 20px;
}
.post-profile-box {
  /* background-color: red; */
}
.profile-name {
  /* background-color: blue; */
  height: 50px;
}
.p-1 {
  color: white;
  font-weight: 600;
}
.p-2 {
  position: relative;
  top: -60%;
  color: #b0b3b8;
  font-size: 13px;
}
.caption {
  width: 100%;
  /* background-color: blue; */
}
.caption-p {
  color: #e4e6eb;
  font-weight: 400;
  font-size: 15px;
}
.post-image {
  width: 100%;
  height: 500px;
  object-fit: cover;
}
.reactions {
  width: 100%;
  height: 40px;
  /* background-color: red; */
}
.rect-icon {
  width: 20px;
  height: 20px;
}
.icon1 {
  z-index: 2000;
  position: relative !important;
  left: 10px !important;
}
.icon2 {
  z-index: 1000;
  position: relative;
  left: 5px;
}
.rx-name {
  color: #b1b3aa;
}
.line3 {
  width: 100%;
  background-color: #7e8484;
  height: 1px;
}
.line4{
   width: 100%;
  background-color: #7e8484;
  height: .5px;
  margin-top: 5px;
}
</style>