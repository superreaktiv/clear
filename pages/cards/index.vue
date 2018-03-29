
<template> 
    <section class="cards">
        <Card 
            thumbnail="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT9uRAbh6tgB-L03B2kvBZ465g-oGZu4xiHpN5RK4_Y0TBxFZex"
            title="Title"
            id="1"
            previewText="1244566" />
        <Card 
            thumbnail="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRUNv-XYXJi3qS0kvVaDPdLKi8St5ThoVJhAz7fOwHAT420MRA7"
            title="Title"
            id="2"
            previewText="1244566" />    
        
    </section>
</template>
<script>
import Card from '@/components/Card'
export default {
  components: {
      Card
  }
}
</script>

<style scoped>
.cards{
    display: flex;
    flex-flow: row wrap;
    justify-content: center;
    align-items: center;
}

</style>