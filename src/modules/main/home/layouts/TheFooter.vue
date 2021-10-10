<template>
 <div class="footer">
   <h6>Türkiye</h6>
   <h6>Hakkında</h6>
   <h6>Gizlilik</h6>
   <h6>Katkıda bulun</h6>
   <h6>Ayarlar</h6>
 </div>
</template>

<style scoped>
.footer {
  position: absolute;
  background-color: #191919;
  bottom: 0;
  min-height: 60px;
  width: 100%;
  padding: 15px;
  display: flex;
}

.footer h6 {
  padding: 0 5px 0 5px;
  cursor: pointer;
  color: rgba(255,255,255,.54);
  transition: 0.3s;
}

.footer h6:hover {
  color: white;
  transition: 0.3s;
}

</style>
