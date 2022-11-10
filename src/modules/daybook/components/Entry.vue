<template>
  <div @click="$router.push({name: 'entry', params:{ id: 10}})" class="entry-container mb-3 pointer p-2">
    <div class="entry-title d-flex">
      <span class="text-success fs-5 fw-bold">10,</span>
      <span class="mx-1 fs-5">Noviembre,</span>
      <span class="mx-2 fw-light">2022</span>
    </div>
    <div class="entry-description">
      Ex proident ullamco aliquip adipisicing exercitation elit ut. Proident ea deserunt aliquip elit culpa et esse culpa. Irure excepteur aliqua Lorem aute aute nisi ea reprehenderit Lorem. Consectetur fugiat quis pariatur aliqua eiusmod qui excepteur amet ea minim. Laboris aliquip reprehenderit voluptate eiusmod incididunt ea nostrud fugiat id eiusmod dolore ipsum excepteur occaecat. Et enim est voluptate proident ad deserunt consectetur ad reprehenderit.
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style lang="scss" scoped>
.entry-container {
  border-bottom: 1px solid #2c3e50;
  transition: 0.2s all ease-in;

  &:hover {
    background-color: lighten($color: grey, $amount: 45);
    transition: 0.2s all ease-in;
  }
  .entry-description {
  font-size: 12px;
}
}

</style>
