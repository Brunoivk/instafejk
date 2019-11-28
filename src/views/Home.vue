<template>

 <div class="row">
   <div class="col-1"></div>
    <div class="col-7">
      
      
      <InstagramCard/>
      <InstagramCard/>
      <InstagramCard/>
      <InstagramCard/>
   
    </div>
    
    <div class="col-3">


<div class="naslovna">
        <div class="imagecropper">
            
            <img src="https://instagram.fzag2-1.fna.fbcdn.net/vp/20198afe5475f2c1fc13fd03904b8c40/5E7126CF/t51.2885-19/74945553_546742806156067_2603461105837670400_n.jpg?_nc_ht=instagram.fzag2-1.fna.fbcdn.net" alt="avatar" class="profile-pict">

          </div>
          
          <div class="username"> bruno.nad</div>
          <div class="name"> Bruno Nađ </div>
</div>

      <div class="nas">

        <div class="price">Priče</div>
        <div>
          <a class="pogledajsve1" href="#"><div class="pogledajsve ">Pogledajte sve</div></a>
        </div>


      </div>
    
<div class="nas2">

        <div class="predlazemo">Mi vam predlažemo</div>
        <div>
          <a class="pogledajsve3" href="#"><div class="pogledajsve2 ">Pogledajte sve</div></a>
        </div>


      </div>


      
      
    </div>
   
  </div>

</template>
<script>
// @ is an alias to /src
import InstagramCard from '@/components/InstagramCard.vue'

export default {
  name: 'home',
  components: {
    InstagramCard
  }
}
</script>

<style lang="scss">
.pogledajsve2{
  float: right;
  padding: 10px 10px 0 0px;
 width: 100px;
 font-size: 10px;
 color: black;
 font-weight: bold;
 
}

.predlazemo{
  float: left;
  padding: 20px 20px 0 15px;
  color:grey;
  font-size: 12px;
  font-weight: bold;
  
}

.nas2{
  background-color: white;
  width:100%;
  height: 170px;
  margin: 30px 0 0 0;
}


.pogledajsve{
  float: right;
  padding: 10px 20px 0 50px;
 width: 150px;
 font-size: 10px;
 color: black;
 font-weight: bold;
}

.price{
  float: left;
  padding: 10px 20px 0 15px;
  color:grey;
  font-size: 13px;
  font-weight: bold;
}

.nas{
  background-color: white;
  width:100%;
  height: 300px;
  margin: 100px 0 0 0;
}



.username1 {
position:relative;
    z-index:1;
    width: 100%;
    height: 300px;
    background-color: rgb(189, 24, 24);
    margin-right: 100px;
    
}
.name1{
  
float: left;
position:relative;
    z-index:2;
    
    width: 30%;
    height: 20px;
    background-color: #f90;
}

.sastrane{
  background-color: red;
}

.card{
  margin-bottom:25px;
}
.image-cropper {
    width: 35px;
    height: 35px;
    position: relative;
    overflow: hidden;
    border-radius: 50%;
    float: left;
  background-color: red;
  overflow: hidden;
}
.profile-pict {
  display: inline;
  margin: 0 auto;
  margin-left: 0%; //centers the image
  height: 100%;
  width: auto;
}


.naziv_acc{
  
  text-align: center;
  width: 85px;
  margin:7px 0 0 0;
  font-size: 14px;
  font-weight: bold;
  overflow: hidden;
  
}


.imagecropper {
    width: 50px;
    height: 50px;
    position: relative;
    overflow: hidden;
    border-radius: 50%;
    float: left;
  
  overflow: hidden;
  
}
.profile-pic {
  display: inline;
  margin: 0 auto;
  margin-left: -35%; //centers the image
  height: 100%;
  width: auto;
  
}
.name{
 
  float:left;
position:relative;
width:200px;
padding:0 119px 0 0;
font-size: 13px;
color: rgb(151, 148, 148);
}

.username{
  float: left;
  padding: 0px 0px 0 9px;
  font-size: 16px;

  
}

.slikabruno {
    width: 50px;
    height: 50px;
    position: relative;
    overflow: hidden;
    border-radius: 50%;
    float: left;
  
  overflow: hidden;
  
}
.okvir {
  display: inline;
  margin: 0 auto;
  margin-left: -35%; //centers the image
  height: 100%;
  width: auto;
  
}


</style>