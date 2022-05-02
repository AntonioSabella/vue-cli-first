<template>
    <div class="hello">
        <div class="container">
            <h2>Io sono un Jumbotron</h2>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ab obcaecati nisi repellendus! Voluptas, aliquam mollitia.</p>
        </div>
    </div>
</template>
<script>
export default {
  name: 'HeroJumbo',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
h2 {
    background-color: cornflowerblue;
}

.container {
    width: 1000px;
    height: 500px;
    background-image: url(https://picsum.photos/1000/500);
    background-repeat: no-repeat;
    border-radius: 0.5rem;
    margin: auto;
    position: relative;
}

p {
    color: white;
    position: absolute;
}
</style>
