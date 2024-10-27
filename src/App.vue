<script>
export default {
  data(){
    return{
      name:'Jon Doe',
      status: 'active'
    }
  }
}
</script>

<template>
 <h1>{{name}}</h1>
 <p v-if ="status === 'active'">user is active</p>
 <p v-else-if ="status === 'pending'">user is active</p>
 <p v-else>user is inactive</p>
</template>