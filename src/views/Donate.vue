<template>
<NavBar/>
  <h2>Donate here!</h2>
  <Button name="Donate Today!" color="purple"></Button>
</template>

<script>
import NavBar from "@/components/NavBar.vue"
import Button from "@/components/Button.vue"

export default {
    components: {
        NavBar,
        Button,
    }
}
</script>

<style>

</style>