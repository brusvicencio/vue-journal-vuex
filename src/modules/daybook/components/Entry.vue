<template>
  <div
      @click="$router.push({name:'entry',params:{id:10}})"
      class="entry-container mb-3 pointer p-2">
    <div class="entry-title d-flex">
        <span class="text-success fs-5 fw-bold">15</span>
        <span class="mx-1 fs-5">julio</span>
        <span class="mx-2 fw-light">2021</span>
    </div>
    <div class="entry-description">
      "But I must explain to you how all this mistaken idea of denouncing pleasure and praising pain was born and I will give you a complete account of the system, and expound the actual teachings of the great explorer of the truth, the master-builder of human happiness. No one rejects, dislikes, or avoids pleasure itself, because it is pleasure, but because those who do not know how to pursue pleasure rationally encounter consequences that are extremely painful. Nor again is there anyone who loves or pursues or desires to obtain pain of itself, because it is pain, but because occasionally circumstances occur in which toil and pain can procure him some great pleasure. To take a trivial example, which of us ever undertakes laborious physical exercise, except to obtain some advantage from it? But who has any right to find fault with a man who chooses to enjoy a pleasure that has no annoying consequences, or one who avoids a pain that produces no resultant pleasure?"
    </div>

  </div>
</template>


<style lang="scss" scoped>
.entry-container{
  border-bottom:  1px solid #2c3e50;
  transition:0.2s all ease-in;
  &:hover {
  background-color: lighten($color:grey,$amount:45);
    transition:0.2s all ease-in;
  }
  .entry-container{
    font-size: 12px;
  }
}
</style>