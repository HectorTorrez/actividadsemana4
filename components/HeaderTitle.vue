<template>
    <div id="app">
        <nav class="navbar navbar-light bg-light ">
            <div class="container-fluid ">
                <p class="navbar-brand ">
                    {{title}}
                </p>
            </div>
        </nav>
    </div>
</template>

<script>
export default {
    name:'HeaderTitle',
    props:{
        title: String
    }    
}
</script>