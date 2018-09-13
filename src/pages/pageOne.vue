<template>
    <div class="pageOne">
        <hello-world></hello-world>
    </div>
</template>
<script>
import HelloWorld from '@/components/HelloWorld'
export default {
    name:'PageOne',
    components:{
        HelloWorld
    },
    beforeMout(){
        console.log('this is parents beforeMout')
    },
    mouted(){
        console.log('this is parents mouted')
    },
    beforeCreate(){
        console.log('this is parents beforeCreate')
    },
    created(){
        console.log('this is parents created')
    },
    beforeUpdate(){
        console.log('this is parents beforeUpdate')
    },
    updated(){
        console.log('this is parents updated')
    },
    beforeDestroy(){
        console.log('this is parents beforeDestroy')
    },
    destroyed(){
        console.log('this is parents destroyed')
    }

}
</script>

