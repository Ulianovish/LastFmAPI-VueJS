<template>  
	<span>
		<div id="img1" class="img"></div>
		<div id="img2" class="img"></div>
		<div id="img3" class="img"></div>
		<div id="img4" class="img"></div>
		<div id="img5" class="img"></div>
	</span>
</template>

<script>
export default {
    name: 'spinner'
}
</script>   

<style scoped>


div {
 
  width:100px;
  height:100px;
border-radius:100%;
  position:absolute;
  border: 1px solid red;
  animation: up 1s;
animation-iteration-count: infinite;
  transition:2s;
 border-bottom:none;
  border-right:none;
  	animation-timing-function:linear;
    margin-left: -55px;
	margin-top: -20px;
	left:50%;
	top:50%;

  }
  
  @keyframes up{
   from{transform:rotate(0deg); }
   50%{transform:rotate(180deg);}
   100%{transform:rotate(360deg);}
  }
  #img2{
  width:90px;
  height:90px;
  left:50.35%;
  top:50.7%;
  animation-delay:.2s;

  }
    #img3{
   width:80px;
  height:80px;
    left:50.70%;
  top:51.4%;
  animation-delay:.4s;
  }
    #img4{
   width:70px;
  height:70px;
     left:51.05%;
  top:52.1%;
  animation-delay:.6s;

  }
    #img5{
    width:60px;
  height:60px;
      left:51.40%;
  top:52.8%;
  animation-delay:.8s;

  }
</style>
