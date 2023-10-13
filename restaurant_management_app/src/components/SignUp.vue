<template>
    <img class="logo" src="../assets/3903248.jpg">
    <h1>Sign Up</h1>

    <div class ="register">
        <input type="text" placeholder="Enter Name"/>
        <input type="text" placeholder="Enter Email"/>
        <input type="password" placeholder="Enter Password"/>
        <button>Sign Up</button>
    </div>
</template>

<script>
export default{
    name:'SignUp'
}
</script>
<style>

.logo{
    width:200px;
    height:200px;
    border-radius: 50%;
    overflow: hidden;

}
.register input{
    width: 300px;
    height: 40px;
    padding-left: 20px;
    display: block;
    margin-bottom: 30px;
    margin-right: auto;
    margin-left: auto;
    border: 1px solid teal;
    color: white;

}
.register button{
    width: 330px;
    height: 40px;
    background-color: teal;
    color: white;
    cursor: pointer;
}

</style>