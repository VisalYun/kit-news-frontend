<template>
  <div class="home">
    <Header />
    <div class="main">
      <div class="feed-container">
        <feed-container />
      </div>
      <div class="aside-container">
        <div class="section-container">
          <people-directory />
        </div>
        <div class="section-container">
          <event-container />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import Header from '@/components/Header.vue'
import FeedContainer from '@/components/FeedContainer.vue'
import PeopleDirectory from '@/components/PeopleDirectory.vue'
import EventContainer from '@/components/EventContainer.vue'

export default {
  name: 'HomeView',
  components: {
    Header,
    FeedContainer,
    PeopleDirectory,
    EventContainer
  }
}
</script>

<style scoped>
.main {
  display: flex;
  justify-content: space-between;
  margin: 25px 50px;
}

.feed-container {
  width: 50%;
}

.aside-container {
  width: 40%;
}

.section-container {
  margin-bottom: 20px;
}
</style>
