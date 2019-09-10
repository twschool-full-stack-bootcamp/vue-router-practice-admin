<template>
    <div class="admin-wrapper">
        <div class="sidebar">
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">Products</a></li>
            </ul>
        </div>

        <div class="content-wrapper">
            <!--put your admin pages here-->
            <Home></Home>
        </div>
    </div>
</template>

<script>
    import Home from './admin/Home'
    export default {
        name: 'Admin',
        components: {
            Home
        }
    }
</script>

<style>
    .admin-wrapper{
        display: flex;
    }
    .content-wrapper{
        padding-left:10px;
        background: white;
        width:100%;
        height: calc(100vh - 60px);
    }
</style>
