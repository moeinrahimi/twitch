<template>
<div>
  <!-- <div class="row"> -->
    <!-- <div class="col-md-12"> -->
<nav>
  <!-- <div class="row"> -->
  <!-- <div class="col-md-12">     -->
  <div class="navbar-logo">
  <img src="../public/images/logo1.png" alt="logo">
  <!-- </div> -->
    <!-- </div> -->
  </div>
  <div class="navbar-menu">
    <a href="#">Following</a>
    <a href="#">Browse</a>
    <a href="#">Get Desktop</a>
    <a href="#">Try Prime</a>
    <i class="fa fa-ellipsis-h"></i>
  </div>
  <div class="navbar-search">
  <input type="text" placeholder="Search">
  </div>
  <div class="navbar-right">
    <div class="navbar-right-icons">
      <i class="fa fa-crown"></i>
      <i class="fa fa-bell"></i>
  </div>
  <div class="navbar-profile">
    <img src="https://static-cdn.jtvnw.net/user-default-pictures/0ecbb6c3-fecb-4016-8115-aa467b7c36ed-profile_image-70x70.jpg" alt="">
      <div class="navbar-right-profile-name">
        <span>  eleventory</span>
        <span>away</span>
      </div>
  </div>
</div> 
      
  
</nav>
<!-- </div>
</div> -->
 <div class="row">
    <div class="col-md-12">
        <div class="sidebar">
          <div class="row">
            <div class="col-md-12 ">
              <div class="header">
                <p>Followed Channels</p>
              </div>
            </div>
          </div>
          <div class="row center-md">
            <div class="col-md-11">
              <div class="border-bottom"></div>
            </div>
          </div>
          <div class="row center-md">
          <div class="col-md-11">
              <div class="streamers">
                
                
                <div class="streamer-box">
                  <div class="row start-md">
                    <div class="col-md-2">
                    <div class="avatar">
                    <img src="https://static-cdn.jtvnw.net/jtv_user_pictures/7ed5e0c6-0191-4eef-8328-4af6e4ea5318-profile_image-70x70.png"> 
                    </div>
                  </div>
                    <div class="col-md-7 ">
                      <div class="game-info">
                      <div class="game-name">
                      <span>shroud</span>
                    </div>
                    <div class="game-name">
                      <span>PLAYERUNKNOWaaaaaaaaaaaaaa</span>
                    </div>
                    </div>
                    </div>
                    <div class="col-md-3">
                    <div class="viewers-count">
                      <div class="row center-md ">

                        
                      <div class="red-dot"></div>
                      <div>39,547</div>
                      </div>  
                      </div>
                    
                    </div>
                  </div>
                  
                  </div>
                  
 
 
   
                  

                  
                </div>
                <div class="show-more">
                <a href="">Show More</a>
                </div>
                <div class="row start-md">
                  <div class="col-md">
                    <div class="friends-sidebar">
                      <p>online firneds</p>
                      <div class="border-bottom"></div>
                      <p id="no-one">None of your Friends are online. Get out there and add more!</p>
                    </div>
                    
                  </div>
                </div>
                <div class="row start-md">
                  <div class="col-md">
                    <p>Recommended Channels</p>
                      <div class="border-bottom"></div>
                    <div class="recommended-channels">
                      
                      <div class="row start-md">
                    <div class="col-md-2">
                    <div class="avatar">
                    <img src="https://static-cdn.jtvnw.net/jtv_user_pictures/ziggydlive-profile_image-7c551aab8c3233e6-70x70.jpeg"> 
                    </div>
                  </div>
                    <div class="col-md-7">
                      <div class="game-info">
                      <div class="game-name">
                      <span>shroud</span>
                    </div>
                    <div class="game-name">
                      <span>PLAYERUNKNOW</span>
                    </div>
                    </div>
                    </div>
                      
                    </div>
                    
                  </div>
                </div>
                  
                
              </div>
                <div class="row">
                  <div class="col-md">
                    <div class="searchbar">
                      <input type="text" placeholder="search to add friends">
                    </div>
                  </div>
                </div>
                
            </div>
          </div>
        </div>
        
    </div> 
    
    
</div>
</div>
</template>
<script>
import HelloWorld from "./components/HelloWorld.vue";
require("../public/flexboxgrid.min.css");
require("../public/normalize.css");
export default {
  name: "app",
  components: {
    HelloWorld
  }
};
</script>

<style>
/* navbar */
nav {
  height: 50px;
  background: #4b367c;
  display: flex;
  align-items: center;

}
a{
  color: var(--text-color)
}
.navbar-menu{
  display: flex;
  justify-content: space-around;
  flex: 0.5;
}
.navbar-menu i{
  color : #fff;
}
.navbar-logo img {
height: 50px;
width: 50px;
}
.navbar-search input{
  width:400px;
  height: 30px;
  margin-left:20px;
}
.navbar-right{
  display: flex;
  justify-content:flex-end;
  flex: 1;
}
.navbar-right-icons { 
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin-right: 15px;
  width: 50px;
}
.navbar-right-icons i{ 
  color : #fff
}
.navbar-profile{
  width:240px;
  display: flex;
}
.navbar-profile img{
  height: 30px;
  width: 30px;
}
.navbar-right-profile-name{
  display: flex;
  flex-direction: column;
  margin-left: 10px;
  font-size: 14px;
  color : var(--text-color)
}
/* sidevar */
@media (max-width: 1029px){

 }
:root {
  --text-color: #9eb5c0;
  --text-color-hover: #75706e;
}

body {
  background: #faf9fa;
  font-family:Helvetica Neue,Helvetica,Arial,sans-serif;
}
.sidebar {
  background: #17141f;
  width: 240px;
  height: 759px;
  margin: 0;
  padding: 0;
}
.border-bottom {
  border-bottom: 2px solid #2c2541;
  /* width : 90%; */
}
.header p {
  margin: 10px;
}
p {
  color: #9eb5c0;
}

.streamers {
  /* background: red; */
  margin-top: 10px;
}
.avatar img {
  width: 30px;
  height: 30px;
}
.game-name span {
  font-size: 12px;
  color: #637081;
}
.viewers-count {
  margin-top: 18px;
}
.viewers-count div {
  font-size: 12px;
  color: #637081;
}
.game-info {
  margin: -6px;
  text-overflow: ellipsis;
  white-space: nowrap;
  overflow: hidden;
}
.red-dot {
  background: red;
  width: 5px;
  height: 5px;
  border-radius: 50%;
  align-self: center;
  margin-right: 5px;
}
.show-more {
  display: flex;
  align-items: flex-end;
  justify-content: flex-end;
}
a {
  text-decoration: none;
}
a:hover {
  color: var(--text-color-hover) !important;
}
.show-more a {
  color: var(--text-color);
  font-size: 12px;
  line-height: 3em;
}
.friends-sidebar p:last-child {
  font-size: 12px;
}
.recommended-channels {
  margin-top: 10px;
}
</style>
