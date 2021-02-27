<template>
<b-container class="bv-example-row">
  <b-row align-v="center">
    <JobCard/>
    <JobCard/>
    <JobCard/>
    <JobCard/>

  </b-row>
</b-container>
</template>

<script>
// @ is an alias to /src
import JobCard from '@/components/JobCard.vue'

export default {
  name: 'Home',
  components: {
     JobCard
  
  }
}
</script>
