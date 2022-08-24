<template>
   <div class="left-child-div">
            <img :src="image" class="left-profile ms-2" alt="">
            <h6>{{ title }}</h6>
   </div>
</template>

<script>
export default {
  name: 'LeftBox',
  props: ['image','title']
}
</script>

<style>
.left-profile{
    width: 40px;
    height: 40px;
    border-radius: 50%;
    object-fit: cover;
}
h6{
  font-weight: 600;
  color: white;
  margin-left: 5%;

}
.left-child-div{
  display: flex;
  /* background-color: red; */
  height: 55px;
  border-radius: 15px;
  /* justify-content: center; */
  align-items: center;
}
.left-child-div:hover{
    background-color: #3d4041;
    cursor: pointer;
}
</style>