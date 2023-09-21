<template>
    <div>
        <PostVue :data="data"/>
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
