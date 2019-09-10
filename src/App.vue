<template>
    <div id="app">
        <div class="header">Welcome to Vue router application</div>
        <div class="main">
            <!--TODO: put your content here-->
            <Admin />
        </div>
        <div class="footer">@copyright</div>
    </div>
</template>
<script>
    import Admin from './pages/Admin'
    export default {
        name: 'App',
        components: {
            Admin
        }
    }
</script>

<style>
    body,#app{
        font-size:12px;
        height:100%;
        padding: 0;
        margin: 0;
    }
    .main{
        min-height:400px;
        background: ghostwhite;
    }
    .header{
        background:azure;
        line-height:30px;
    }
    .footer{
        line-height:30px;
        background: cadetblue;
    }
</style>
