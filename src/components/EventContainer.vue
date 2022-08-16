<template>
    <div class="directory">
        <h2>Upcoming Event</h2>
        <div class="event-container">
            <event />
            <event />
            <event />
        </div>
    </div>
</template>

<script>
import Event from "./Event.vue";

export default {
    name: "EventContainer",
    components: {
        Event
    },
    setup(){

    }
}
</script>

<style scoped>
.directory {
    padding: 20px;
    background-color: #fbfbfb;
}

.event-container{
    margin-top: 10px;
}
</style>