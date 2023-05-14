<script>
    let nombre = '';
</script>

<div>
    <h2>Hola <i>{nombre}</i></h2>
    <input on:keyup={(e)=> nombre=e.target.value} type="text">
</div>

<style>
    div{
        margin: 10px;
        width: 50%;
        background-color: aqua;
        border-radius: 20px;
    }
    h2{
       margin:10px; 
    }
    input{
        margin:10px;
        width:90%;
        border: 0;
    }
</style>
