<template>
    <div>
        <hr>
        <h2>IN: Component: Server</h2>
        <button @click='changeStatus'>Update</button>
        <p>Status: {{status}}</p>
        <hr>
    </div>
</template>
<script>
export default {
    data: function(){
        return {status: 'Server : Critical'}
    },

    methods:{
        changeStatus(){
            this.status = 'Server: Normal';
        }
    }
    
}
</script>

