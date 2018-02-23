<template>
    <div id="visitenkarte">
        <img src="/BAUERNHOF_LOGOTYPE_POS.svg" alt="Bauernhof Logo">
        <p>
            Anja Pfäffli, Deisswilstrasse 1 <br>
            3256 Bangerten
        </p>
        <a href="tel:+41793325825"><span>Tel</span>079 332 5825</a><br>
        <a href="mailto:info@bangerten.ch">info@bangerten.ch</a>
    </div>
   
</template>

<script>
export default {};
</script>

<style scoped>
#visitenkarte {
  font-family: Arial, Helvetica, sans-serif;
}

a {
  text-decoration: none;
  color: black;
}

@media screen and (max-width: 768px) {
  #visitenkarte {
    -webkit-transform: rotate(-90deg);
    -moz-transform: rotate(-90deg);
    -ms-transform: rotate(-90deg);
    -o-transform: rotate(-90deg);
  }
}
</style>