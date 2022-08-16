<template>
    <div class="feed">
        <img class="big-image" src="@/assets/temp.jpg" />
        <div class="img-preview">
            <img class="small-image" src="@/assets/temp.jpg" />
            <img class="small-image" src="@/assets/temp.jpg" />
            <img class="small-image" src="@/assets/temp.jpg" />
            <img class="small-image" src="@/assets/temp.jpg" />
        </div>
        <h3 class="news-title">Launching event of KIT News</h3>
        <p class="news-preview">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Blanditiis repudiandae, maxime atque expedita error reiciendis enim fugit minima minus aliquam molestiae! Eveniet quam iusto nostrum quia tempore sint natus voluptatem.
        Placeat tempora tempore illo nam, minima atque rerum vero temporibus necessitatibus? Ex quae veritatis hic rem eos reiciendis, quaerat officiis quas beatae tempora illo non, molestiae eum modi nisi eaque.</p>
        <div class="news-footer">
            <p>By: John Doe</p>
            <p>Date: 2022-08-16 12:00:00</p>
        </div>
    </div>
</template>

<script>
export default {
    name: "Feed",
    setup(){}
}
</script>

<style scoped>
.feed {
    margin: 20px 0px;
    border-bottom: 1px solid #000;
}

.big-image{
    display: block;
    width: 100%;
    height: auto;
    border-radius: 5px;
}

.img-preview{
    display: flex;
    justify-content: space-between;
    margin: 5px 0px 0px;
}

.small-image {
    display: block;
    width: 24%;
    height: auto;
    border-radius: 5px;
}

.news-title{
    font-size: 2em;
    margin: 5px 0px;
}

.news-preview{
    text-align: justify;
}

.news-footer{
    display: flex;
    justify-content: space-between;
    margin: 25px 0px 5px;
}
</style>