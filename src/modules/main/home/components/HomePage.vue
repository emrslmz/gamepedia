<template>
  <div class="home">
   <div class="home-header">
     <h1>Gamepedia</h1>
   </div>
    <div class="home-search-box col-4">
      <span class="home-search-box__icon"><i class="fas fa-search"></i></span>
      <input class="home-search-box__input" type="text" placeholder="Bir şeyler arayın..." />
    </div>
    <div class="home-search-box__result col-2">
      <div><i class="fas fa-arrow-alt-circle-right"></i> dsadasdasasd</div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HomePage',
};
</script>

<style scoped>
.home {
  color: white;
  min-height: 60vh;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}

.home-search-box {
  display: flex;
  justify-content: center;
  align-items: center;
  padding-top: 15px;
}

.home-search-box__icon {
  border-radius: 50px 0 0 50px;
  background-color: white;
  color: rgba(32,33,36,1);
  font-size: 16px;
  display: flex;
  justify-content: start;
  align-items: center;
  height: 50px;
  padding-left: 15px;
}

.home-search-box__input {
  border-radius: 0 50px 50px 0;
  background-color: white;
  width: 100%;
  height: 50px;
  outline: 0;
  padding-left: 15px;
  border: none;
  outline: none;
}

.home-search-box__result {
  color: #444343;
  background-color: white;
  border-radius: 50px;
  min-width: 20%;
  padding: 5px 10px 5px 10px;
  margin-top: 20px;
  transition: 0.4s;
}

.home-search-box__result:hover {
  box-shadow: 0 0 8px #191919;
  transition: 0.4s;
  cursor: pointer;
  background-color: #dcdcdc;
}
</style>
