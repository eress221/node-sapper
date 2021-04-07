<svelte:head>
    <title>TEST</title>
</svelte:head>

<script>
    var test1 = "color:white;";

function f() {
        alert(document.querySelector("#test").className);
    }
</script>

<div id=test class="test" on:click="{f}" style={test1}><span>test</span></div>

<style>
    div{background-color:red;}
</style>
