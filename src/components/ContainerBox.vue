<template>
    <div>
        <PostVue :data="data"/>
        <PostVue/>
        <PostVue/>
    </div>
</template>

<script>
import PostVue from './PostData.vue'


export default {
    name: 'containerVue',
    components :{
        PostVue
    },
    props : {
        data : Array
    }

    
}
</script>


<style >
</style>
