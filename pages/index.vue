<template>
  <div class="home-page">
    <section class="intro">
      <h1>Get the latest tech news</h1>
    </section>
    <section class="featured-posts">
      <PostPreview 
      id="1"
      thumbnail = "https://i.guim.co.uk/img/media/e6d40cb644691606c6f9d9779fb6504d5b254c4a/0_333_5000_3000/master/5000.jpg?width=620&quality=45&auto=format&fit=max&dpr=2&s=6ea7e1d5600e5c19a9d288489a43c072"
      title = "Hello there"
      previewText = "Lorem ipsum dolor sit, amet consectetur adipisicing elit. Praesentium ea eaque quaerat repudiandae minus, neque, vitae reiciendis et veritatis laboriosam ipsam corrupti delectus alias perspiciatis quos quisquam, nobis tempora distinctio?"
      />
      <PostPreview 
      id="2"
      thumbnail = "https://i.guim.co.uk/img/media/e6d40cb644691606c6f9d9779fb6504d5b254c4a/0_333_5000_3000/master/5000.jpg?width=620&quality=45&auto=format&fit=max&dpr=2&s=6ea7e1d5600e5c19a9d288489a43c072"
      title = "Hello there"
      previewText = "Lorem ipsum dolor sit, amet consectetur adipisicing elit. Praesentium ea eaque quaerat repudiandae minus, neque, vitae reiciendis et veritatis laboriosam ipsam corrupti delectus alias perspiciatis quos quisquam, nobis tempora distinctio?"
      />
     
    </section>
  </div>
</template>

<script>
import PostPreview from '@/components/Posts/PostPreview'
export default {
  components: {
    PostPreview
  }
};
</script>

<style>.intro {
  height: 300px;
  position: relative;
  padding: 30px;
  box-sizing: border-box;
  background-position: center;
  background-size: cover;
  background-image: url('~assets/images/main-page-background.jpg');
}

.intro h1 {
  position: absolute;
  top: 10%;
  left: 5%;
  width: 90%;
  font-size: 1.5rem;
  color: black;
  background-color: rgb(211, 211, 211);
  padding: 10px;
  border-radius: 10px;
  box-shadow: 3px 3px 3px black;
  box-sizing: border-box;
  border: 1px solid black;
}

@media (min-width: 768px) {
  .intro h1 {
    font-size: 2rem;
  }
}

.featured-posts {
  display: flex;
  padding: 20px;
  box-sizing: border-box;
  flex-wrap: wrap;
  align-items: center;
  justify-content: center;
}


</style>
