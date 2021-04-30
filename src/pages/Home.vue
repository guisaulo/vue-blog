<template>
  <Profile/>
  <Feed/>
</template>

<script>
import Profile from '../components/Profile.vue'
import Feed from '../components/Feed.vue'

export default {
  name: 'Home',
  components: { Profile, Feed }
}
</script>