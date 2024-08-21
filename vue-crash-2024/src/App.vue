<script>
  export default {
    data() {
      return {
        name: 'John Doe',
        status: 'pending', 
      }
    }
  }
</script>

<template>
  <h1>Vue Jobs</h1>
  <p v-if="status === 'active'">User is active</p>
  <p v-else-if="status === 'pending'">User is pending</p>
  <p v-else>User is inactive</p>
</template>