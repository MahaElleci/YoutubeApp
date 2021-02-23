<template>  
<header> 
    <nav class="main-nav">
    <div class="nav-bar">  
    <HeaderSearch></HeaderSearch>  
       </div> 
    </nav>
    </header> 
</template> 


<script>
import HeaderSearch from "./header-search";
export default {
  name: "HeaderBar",
  components: { HeaderSearch },
};
</script>  

<style lang="scss"> 
.main-nav{ 
position: relative;
  .nav-bar {
   padding: 2rem;
   background: red;
   width: 100%;
  } 
}
</style>

