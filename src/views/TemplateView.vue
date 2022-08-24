<template>
  <div>
    <nav-component/>
    <div class="row">
       <left-bar/>
       <div class="col-md-6"></div>
       <div class="col-md-3 right-bar">
          <div class="d-flex justify-content-between mb-2">
            <h6>Your Pages and profiles</h6>
            <a href="" class="dot-r-m">
              <i class="fa-solid fa-ellipsis"></i>
            </a>
          </div>
          <div class="ms-3">
            <left-box :title="`L a S T Benchers`" :image="`https://scontent.fbir1-1.fna.fbcdn.net/v/t1.6435-9/82911741_151452926278114_7905798915096576000_n.jpg?_nc_cat=101&ccb=1-7&_nc_sid=09cbfe&_nc_ohc=OWe5xnQXQIIAX-lLfYZ&_nc_ht=scontent.fbir1-1.fna&oh=00_AT_59Eg6sXw7kdggFyMRn_bkxfLFQ2FL80KDwsBJUD1lOg&oe=632C3114`" />

          </div>
          <div class="ms-5 mt-2 d-flex notif">
            <i class="fa-regular fa-bell"></i>
            <p class="ms-4">20+ Notifications</p>
          </div>
           <div class="ms-5 d-flex notif">
            <i class="fa-solid fa-marker"></i>
            <p class="ms-4">Create Promotions</p>
          </div>
          <div class="line2"></div>
          <div class="d-flex justify-content-between mt-3">
            <h6>Friend Requests</h6>
            <a href="">See all</a>
          </div>
          <!-- Friend Requests -->
          <div class="zay mb-3 ms-2 mt-2">
            <div class="d-flex f-r-d">
              <img src="https://scontent.fbir1-1.fna.fbcdn.net/v/t1.6435-9/201919810_1147065982455221_4555460157877966119_n.jpg?_nc_cat=106&ccb=1-7&_nc_sid=174925&_nc_ohc=g6VSYI648HYAX89e0SX&_nc_oc=AQm-JXpM2OXvKg-VHhq61wvvv8U2IMggtC3HdKy71pnv-34QUlXoKRckcqxI1jDaGTIzJ3HQHJAdM5t1LvOKUk5l&_nc_ht=scontent.fbir1-1.fna&oh=00_AT-t-HW6NjdzLUEpQO5-siE23yr4CA0Upymn1jlx7HxY5w&oe=632B110C" class="zay-img" alt="">
              <div class="zay-body">
                <div class="d-flex ms-3 justify-content-between">
                  <p class="zay-name">
                    Niskarsh Shrestha
                  </p>
                  <p class="time">1 h</p>
                </div>
                <div class="d-flex ms-3 req-btn justify-content-between">
                  <button class="confirm-btn">Confirm</button>
                  <button class="delete-btn">Delete</button>
                </div>
              </div>
            </div>
          </div>
          <div class="line2"></div>
       </div>
    </div>

  </div>
</template>

<script>
import NavComponent from '@/components/NavComponent.vue'
import LeftBox from '@/components/LeftBox.vue'
import LeftBar from '@/components/LeftBar.vue'
export default {
 name: 'TemplateView',
 components: {NavComponent,LeftBox,LeftBar},

}
</script>

<style>
.right-bar{
  padding-left: 20px;
  /* position: sticky; */
  padding-top: 20px ;
  /* background-color: red; */
}
.req-btn{
  position: relative;
  top: -15%;
}
.delete-btn{
   width: 120px;
  height: 40px;
  color: white;
  background-color: #313030;
  border-radius: 10px;
  font-weight: 600;
  border: none;
}
.f-r-d{
  padding: 10px;
}
.zay{
  width: 100%;
  /* background-color: blue; */
  height: 90px;
  border-radius: 10px;
}
.zay:hover{
  background-color: #3d4041;
  cursor: pointer;
}
.time{
  color: rgb(200, 189, 189);
}
.zay-body{
  /* background-color: green; */
  height: 65px;
  width: 100%;
}
.zay-img{
  height: 65px;
  width: 65px;
  border-radius: 50%;
  object-fit: cover;
}
.confirm-btn{
  width: 125px;
  height: 40px;
  color: white;
  background-color: #2275E1;
  border-radius: 10px;
  font-weight: 600;
  border: none;
}
h6{
    color: rgb(200, 189, 189);

}
.zay-name{
  font-size: 17px;
  font-weight: 600;
  color: rgb(237, 228, 228);
}
.dot-r-m{
  color: rgb(200, 189, 189);
}
.notif{
  color: #A1A2A7;
  font-weight: 500;
}
.notif p{
  font-size: 14px;
  font-weight: 600;
}
.line2{
  width: 95%;
  background-color: #828c8c;
  height: 1px;
  position: relative;
  left: 5%;
}
</style>