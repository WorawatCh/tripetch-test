<template>
  <div class="playerImg-1 position-absolute">
    <img src="../assets/footballer1.png" class="img-fluid w-50" alt="Responsive image">
  </div> 
   <div class="row">
    <div class="col-6  section-1">
    </div>
    <div class="col-6 text-start  section-1">
      <h1>ATHLETS</h1>
      <div class="pt-5 pb-3 section-subhead">
        <span class="position-absolute">01<img src="../assets/Rectangle.svg" class="rectangle"/></span><h3>CONNECTION</h3>
      </div>
      <p >Connect with coaches directly, you can ping coaches to view profile.</p>
    </div>
    <div class="col-6 section-2">
    </div>
    <div class="col-6 section-2 text-start align-middle">
      <h3>COLLABORATION</h3>
      <p>Work with other student athletes to increase visability. When you share and like other players videos it will increase your visability as a player. This is the team work aspect to Surface 1.</p>
    </div>
    <div class="col-6 section-3"></div>
    <div class="col-6 section-3 text-start align-middle">
      <h3>GROWTH</h3>
      <p>Resources and tools for you to get better as a student Athelte. 
        Access to training classes, tutor sessions, etc</p>
    </div>
  </div>

  <div class="playerImg-2 position-absolute">
    <img src="../assets/footballer2.png" class="img-fluid w-75 pt-5" alt="Responsive image">
  </div> 
   <div class="row">
     <div class="col-6 text-start section-4-content pt-5">
       <h1>PLAYERS</h1>
       <div class="pt-5 pb-3 section-subhead">
         <span class="position-absolute">01<img src="../assets/Rectangle.svg" class="rectangle"/></span><h3>CONNECTION</h3>
       </div>
       <p >Connect with talented athlete directly, you can watch their 
 skills through video showreels directly from Surface 1.</p>
     </div>
    <div class="col-6  section-4">
    </div>
    <div class="col-6 section-5-content text-start">
      <h3>COLLABORATION</h3>
      <p>Work with recruiter to increase your chances of finding
talented athlete.</p>
    </div>
    <div class="col-6 section-5-content">
    </div>
    <div class="col-6 section-6-content text-start">
      <h3>GROWTH</h3>
      <p>Save your time, recruit proper athlets for your team.</p>
    </div>
    <div class="col-6 section-6-content"></div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.rectangle{
  vertical-align: bottom;
}
.playerImg-1 {
  left: -200px;
}
.playerImg-2 {
  right: 0px;
}
.section-1,.section-4-content{
  height: 345px;
}
.section-2,.section-5-content{
  background: #F5F4F9;
  height: 256px;
}
.section-3{
  background: #5E3DB3;
  height: 297px;
}
h1{
  color:#E7E7E7;
}
h3{
  color: #C2C2C2;
}
.section-subhead span, .section-subhead h3{
  display: inline;
}
.section-6-content{
 background: #090C35;
 height: 297px;
}
.section-6-content p{
  color: #ffffff; 
}
.section-4-content,.section-5-content,.section-6-content{
  padding-left: 15vw
}
</style>
