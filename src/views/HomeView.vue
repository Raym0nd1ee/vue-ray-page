<script>
import axios from 'axios'
import { ref } from 'vue'
const album = ref()
export default {
    setup() {
    axios.get('https://jsonplaceholder.typicode.com/albums')
.then((res)=>album.value=res.data)
return {album}
}
}



</script>
<template>
    <h1>Home Page</h1>
<div v-for="item in album" :key="item.id">
    {{ item.title }}
</div>

</template>
 
 

    


