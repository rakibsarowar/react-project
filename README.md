"# vue- first project"

Learned how to create App and mount by vue js

create App: 
const app = Vue.createApp({
    data() {
        return {
            product: 'socks',
            // solution
            description: "A warm fuzzy of socks."
            // solution
        }
    }
})

mounted: 
<script>
    const mountedApp = app.mount('#app')
</script>
