<template>
    <li class="col">
        <img :src="thumb" alt="">
        <h3>{{ title }}</h3>
    </li>
</template>
  
<script>
export default {
    props: {
        thumb: String,
        title: String
    }
}
</script>

<style lang="scss" scoped>
.col{
    flex-basis: calc(100% / 6 - 50px);
    flex-grow: 1;
    gap: 10px;


    h3 {
        font-size: 16px;
        font-weight: 200;
        margin-top: 15px;
        
    }

    img {
        width: 200px;
        aspect-ratio: 1/1;
        object-fit: cover;
        object-position: top;
    }
}

</style>