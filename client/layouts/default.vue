<template>
  <div>
    <Header />
    <div class="container">
      <Bunner />
      <Nuxt/>
    </div>
    <Footer />
  </div>  
</template>

<style scoped>
main{
    min-height: calc(100vh - 60px - 392px - 160px);
    padding: 10px 0;
}
h3{
    font-size: 18px;
    font-weight: 600;
    color: #9f6212;
}
</style>