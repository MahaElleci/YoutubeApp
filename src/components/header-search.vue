<template>  
<div class="search-bar-wrapper">
    <input class="search-bar" type="text" />  
     <i class="fas fa-search"></i>
</div>
</template> 

<script>
export default {
  name: "HeaderSearch",
};
</script> 

<style lang="scss" scoped>
.search-bar-wrapper {
  position: absolute;
  top: 0;
  right: 0;
  margin: 0.9rem 6.7rem;
  padding: 0.5rem; 
  display: flex;  
  justify-content: space-between;
  margin-top: 0.9rem;
  i {
      color: #fff;
  }
}
</style>