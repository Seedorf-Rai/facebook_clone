<template>
  <div class="story">
    <img
      :src="storyImage"
      class="story-story"
      alt=""
    />
    <div class="story-profile">
      <img
        :src="profilePic"
        class="s-p-img"
        alt=""
      />
    </div>
    <div class="other_name">
      <p class="text-white">{{ name }}</p>
    </div>
  </div>
</template>

<script>
export default {
    name: 'StoryComp',
    props: ['profilePic','storyImage','name']
};
</script>

<style>
.story{
   width: 124px;
  height: 200px;
  background-color: #2E89FF;
  margin-left: 10px;
  border-radius: 12px;
  position: relative;
  overflow: hidden;
}
.story-profile{
  position: absolute;
  top: 16px;
  left: 16px;
  background-color: #2E89FF;
  height: 50px;
  width: 50px;
  border-radius: 50%;

  display: flex;
  justify-content: center;
  align-items: center;
  object-fit: cover;

}
.s-p-img{
  width: 40px;
  height: 40px;
  border-radius: 50%;
  object-fit: cover;
}
.story-story{
   width: 124px;
  height: 200px;
  object-fit: cover;
  opacity: 0.87;
  transition: all 1s;
}
.story-story:hover{
  scale: 1.05;
  cursor: pointer;
}
.other_name{
  /* background-color: red; */
  color: white;
  position: absolute;
  top: 150px;
  margin-left: 10px;
  font-weight: 500;
  font-size: 13px;
}
</style>