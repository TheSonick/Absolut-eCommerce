<template>
  <div>
    <Header />
    <div class="container">
      <Nuxt/>
    </div>
    <Footer />
  </div>  
</template>

<style scoped>
main{
    display: grid;
    grid-template-columns: 1fr 3fr;
    row-gap: 10px;
    column-gap: 10px;
    min-height: calc(100vh - 60px - 160px);
    margin-top: 70px;
    padding-bottom: 10px;
}
</style>