<template>
    <section class="empl">
       
        <ChatWindow/>
<InputBar/>
    </section>
</template>

<script>
import InputBar from "@/components/InputBar.vue";
import ChatWindow from "@/components/ChatWindow.vue";
export default {
name:"Employe",
components:{
    InputBar,
    ChatWindow,
}
}
</script>

<style lang="scss">

</style>
