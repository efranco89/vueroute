<template>
  <div class="users">
    <h1>Informacion del Usuario</h1>
    <router-link :to="{ name:'users', params: {id: user } }"
      v-for="(user, index) in usersArray" :key="index">
      <button type="button" name="button">{{ user }}</button>
    </router-link>
    <User/>
  </div>
</template>
<script>
  import User from '@/components/User.vue';
  export default{
    components: {
      User
    },
    data(){
      return{
        usersArray: [
          'efranco', 'carlos', 'luisa', 'camila'
        ]
      }
    }
  }
</script>
