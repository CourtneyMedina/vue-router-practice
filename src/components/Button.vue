<template>
  <button :name="name" :style="btncolor">{{name}}</button>
</template>

<script>
export default {
    props: {
        name: String,
        color: String,
    },
    setup(props){
        let btncolor = "background-color:"+props.color+";color:whitesmoke;";
        return {btncolor}
    }
}
</script>

<style>


</style>