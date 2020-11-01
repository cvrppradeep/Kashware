<template>
  <div id="navigation-mobile">
    
    <ul>
      <li>kard</li>
      <li >kardless</li>
      <li >security</li>
      <li >rewards</li>
      <li>
<img class="getappbtn" src="../assets/get the app button.png" />
         
      </li>
    </ul>
   
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
#navigation-mobile {
  padding: 20px 0 0 0;

  ul {
    list-style: none;
    width: 200px;
    padding-left: 40px;

    li {
      // color: rgba(0, 0, 0, 0.2);
      
      font-size: 1rem;
      font-weight: bold;
      margin-bottom: 20px;
      cursor: pointer;
      color: white;

      &:hover {
        color:white;
      }
    }
  }
.getappbtn{
     width: 5rem;
   }
 }
</style>
