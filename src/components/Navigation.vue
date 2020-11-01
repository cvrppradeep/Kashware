<template>
  <div id="navigation">
    <div class="flex">
<div>
  <!-- <div class="logo1"></div> -->
<img class="logo" src="../assets/logo.png" />
</div>
<div>
    <ul class="nav-font">
      <li>kard</li>
      <li class="p-l">kardless</li>
      <li class="p-l">security</li>
      <li class="p-l">rewards</li>
      <li>
<img class="getappbtn p-l" src="../assets/get the app button.png" />
         
      </li>
    </ul>
 
    </div>
</div>
  </div>
  
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
#navigation {
  // display: flex;
  // width: 100%;
  // margin-bottom: 50px;
  background: #191919 0% 0% no-repeat padding-box;
box-shadow: 0px 3px 6px #BEBEBE1A;
opacity: 1;
backdrop-filter: blur(5px);
-webkit-backdrop-filter: blur(5px);
top: 0px;
left: 0px;
width: 1920px;
// height: 100px;

  ul {
    display: flex;
    list-style: none;
    padding: 0;
    
    li {
      // font-size: 2rem;
      // padding: 2px 10px;
      cursor: pointer;

      &:hover {
        color: #7ca971;
      }
    }
  }
 
  
  .flex{
    display: flex;
    flex-direction: row;
    justify-content: space-around;
    align-items: center;
  }
   .logo{
 width: 2rem;
   }
   .getappbtn{
     width: 5rem;
   }
.appbutton{
  top: 26px;
left: 1522px;
width: 153px;
height: 49px;
background: transparent url('../assets/get the app button.png') 0% 0% no-repeat padding-box;
opacity: 1;
}
.nav-font{
  text-align: left;
font: normal normal medium 30px/36px SF Pro Text;
letter-spacing: 0px;
color: #F8F6F1;
opacity: 1;
}
.p-l{
  padding-left: 2rem;
}
  .search {
    position: relative;
    width: 100%;
    max-width: 400px;

    input {
      border: none;
      outline: none;
      width: calc(100% - 80px);
      padding: 15px 60px 15px 20px;
      margin: 0;
      border-radius: 20px;
      background-color: #efefef;
      font-family: "Segoe UI", Tahoma;
      font-size: 1rem;
    }

    i {
      position: absolute;
      right: 20px;
      top: 15px;
      font-size: 1.6rem;
      color: #aaa;
      cursor: pointer;
    }
  }
}
</style>
