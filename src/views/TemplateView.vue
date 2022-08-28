<template>
  <div>
    <nav-component />
    <div class="row mt-5">
      <left-bar />
      <div class="col-md-6 main-section py-4">
        <!-- Story Section -->
        <story-section />
        <!-- Story Section Ends -->
        <!-- Status Bar -->
        <status-bar />
        <!-- Status Bar Ends -->
        <!-- Create Room Section -->
        <create-room />
        <!-- Create Room Section Ends -->
        <!-- Post Section -->
        <post-comp :userPicture="`https://scontent.fbir1-1.fna.fbcdn.net/v/t39.30808-6/301134064_118298224309390_6670996927583669228_n.jpg?_nc_cat=106&ccb=1-7&_nc_sid=5cd70e&_nc_ohc=R4yWMfB4zfsAX-JYK7L&_nc_ht=scontent.fbir1-1.fna&oh=00_AT9aD_plEwPNDiLa-B-D7h08XfeAiTy-uHO1ZMUTryWczA&oe=630F9E08`" :userName="`Niskarsh Shrestha`" :time="`4 h`" :caption="`Looking Forward to the game`" :image="`https://scontent.fbir1-1.fna.fbcdn.net/v/t39.30808-6/301913331_128980376541432_5403349440425329040_n.jpg?_nc_cat=1&ccb=1-7&_nc_sid=8bfeb9&_nc_ohc=YuxxYt1eC54AX80Cs7t&_nc_oc=AQnFKcVHyRbZCNnmXJNK_mI4YHRYMaxTzUdHZiw26My9bFohGIFMPAoN5i4CozobypJ-UVstAkulANVICmneqJDl&tn=2CbQhr8TpFc2udLw&_nc_ht=scontent.fbir1-1.fna&oh=00_AT-aNSVKOq_xiJbzQxOw_1mFhWdicJLtQ2CwQQdqBBYWfA&oe=630FF435`"/>
        <post-comp :userPicture="`https://scontent.fbir1-1.fna.fbcdn.net/v/t39.30808-6/240949916_1265829463875534_4995396472475390304_n.png?_nc_cat=1&ccb=1-7&_nc_sid=09cbfe&_nc_ohc=0cth6nXi5uUAX9h87wS&_nc_ht=scontent.fbir1-1.fna&oh=00_AT89LsbGb3aUjdlZ6AXyyxsMCM9RiPs5ODNMFHeg9h7Vbg&oe=630F4C22`" :userName="`R A I Squad`" :time="`4 h`" :caption="`Limbuni paiyee aru k chainthyo ra?`" :image="`https://scontent.fbir1-1.fna.fbcdn.net/v/t39.30808-6/302151837_1508193116305833_5997250245591946911_n.jpg?stp=dst-jpg_p843x403&_nc_cat=110&ccb=1-7&_nc_sid=730e14&_nc_ohc=iEtRVA72tTwAX9LsS_N&_nc_ht=scontent.fbir1-1.fna&oh=00_AT8fDyx5cYuHRZe1mWt6vBMIxpCEyKey9kQCjZq9vjSIpg&oe=6310C25B`"/>
        <post-comp :userPicture="`https://scontent.fbir1-1.fna.fbcdn.net/v/t1.18169-9/17903437_10155554645366840_7299462485287843175_n.png?_nc_cat=1&ccb=1-7&_nc_sid=09cbfe&_nc_ohc=cbP-f3fPh00AX8XuM-b&_nc_oc=AQnN2H00i03uhA48fauqM7YF0IUhqROnniJIH_oruWJ_mY_sykkpiJBMm9Y3paZTuH1UlVlxU35TQhHKxSJjwy32&_nc_ht=scontent.fbir1-1.fna&oh=00_AT9PkxAJlsMAguJp6eITTlvsZc21GeJzy-SI5GjgTLGHag&oe=63303942`" :userName="`9GAG`" :time="`10 h`" :caption="`Hearing problem lol !`" :image="`https://scontent.fbir1-1.fna.fbcdn.net/v/t39.30808-6/301595095_10162392614876840_384326497869497223_n.jpg?stp=cp1_dst-jpg_p843x403&_nc_cat=1&ccb=1-7&_nc_sid=730e14&_nc_ohc=UpMPD-cdxVcAX_3nI2x&tn=2CbQhr8TpFc2udLw&_nc_ht=scontent.fbir1-1.fna&oh=00_AT_AinlfCxzuZwEIwmbwOmqJjS9qi_CUCUHDtiLDJSdhMg&oe=6310DDFF`"/>

        <!-- Post Section Ends -->
      </div>

      <right-bar />
    </div>
  </div>
</template>

<script>
import NavComponent from "@/components/NavComponent.vue";
import LeftBar from "@/components/LeftBar.vue";
import RightBar from "@/components/RightBar.vue";
import StorySection from "@/components/StorySection.vue";
import StatusBar from "@/components/StatusBar.vue";
import CreateRoom from "@/components/CreateRoom.vue";
import PostComp from "@/components/PostComp.vue";
export default {
  name: "TemplateView",
  components: {
    NavComponent,
    LeftBar,
    RightBar,
    StorySection,
    StatusBar,
    CreateRoom,
    PostComp
  },
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