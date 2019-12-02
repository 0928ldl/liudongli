<template>
  <div class="home">
    <span @click="fn()">{{list}}</span>
  </div>
</template>

<script>
import {mapState} from "vuex"
export default {
  name: 'home',
  components: {
   
  },
  methods:{
    fn(){
      console.log('1')
    }
  },
  computed:{
    ...mapState(["list"])
  }
}
</script>
