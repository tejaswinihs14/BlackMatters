<template>
    <div class="page">
        <h1 class="title" >{{title}}</h1>
        <p class="timestamp">{{timestamp}}</p>
        <p class="desc">{{desc}}</p>
        <!-- <div class="avatar"><img :src=" "></div> -->
    </div>
</template>

<script>

    export default {
        name:"Content",
        props: ['title','timestamp','desc','avatar']
       
    }
    
</script>

<style scoped>

.page{
    padding: 20px 30px;
    color: black;
    border-bottom: 2px solid grey;
    margin-top: 5px;
    margin-left: 400px;
    margin-right: 400px;
}

.title{
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    font-size: 32px;
    font-weight: 900;
    color: black;
    margin-bottom: 0px;
}

.timestamp{
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    font-size: 24px;
    font-weight: 700;
    color: rgb(44, 41, 41); 
    margin-top: 0px;  
}

.desc{
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    font-size: 24px;
    font-weight: 500;
    color: rgb(36, 33, 33);
}

.avatar{
    height:100%;
    width:100%;
    border: 1px solid black;
}

</style>