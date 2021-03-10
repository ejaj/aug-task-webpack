<template>
    <div class="welcome">
        <div class="">
            <h1>{{ msg }}</h1>
            <p>
                Augmedix Building, House# 17/C, Near Square Hospital,Panthapath, Dhaka - 1215,
            </p>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'Welcome',
        props: {
            msg: String
        }
    }
</script>