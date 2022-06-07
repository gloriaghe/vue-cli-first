<template>
    <section>
        <div>
            <img alt="logo" src="../assets/logo.png">
            <h1>La mia prima Super App con Vue CLI</h1>
        </div>

    </section>

</template>

<script>
export default {
    name: 'TiTle',
    props: {
        msg: String
    }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
h1 {
    color: palevioletred;
    width: 60%;
    font-size: 30px;
}

div {
    display: flex;
    flex-direction: row;
}
</style>
