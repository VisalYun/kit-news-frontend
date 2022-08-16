<template>
    <div>
        <h2>Latest News</h2>
        <p>As 2022-08-16 22:00:00</p>
        <feed />
        <feed />
        <feed />
    </div>
</template>

<script>
import Feed from "./Feed.vue"

export default {
    name: 'FeedContainer',
    components: {
        Feed
    },
    setup(){}
}
</script>