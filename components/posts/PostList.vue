<template>
 <section class="posts-list">
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

    
</template>
<script>
export default {
    
}
</script>
<style scoped>
.posts-list {
  display: flex;
  padding: 20px;
  box-sizing: border-box;
  flex-wrap: wrap;
  align-items: center;
  justify-content: center;
}

</style>