<template>
    <div class="hello">{{msg}}</div>
</template>

<script>
export default {
    name: 'HelloWorld',
    data() {
        return {
            msg: 'Vue父子组件生命周期顺序'
        }
    },
    beforeMout(){
        console.log('this is child beforeMout')
    },
    mouted(){
        console.log('this is child mouted')
    },
    beforeCreate(){
        console.log('this is child beforeCreate')
    },
    created(){
        console.log('this is child created')
    },
    beforeUpdate(){
        console.log('this is child beforeUpdate')
    },
    updated(){
        console.log('this is child updated')
    },
    beforeDestroy(){
        console.log('this is child beforeDestroy')
    },
    destroyed(){
        console.log('this is child destroyed')
    }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.hello {
    height: 60px;/*px*/
    line-height: 60px;/*px*/
    width: 750px;
    font-size: 32px;/*px*/
    border: 1px solid red;/*no*/
    text-align: center;
}
</style>
