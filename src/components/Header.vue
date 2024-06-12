<template>
  <div>
    
    <div class="header">

        <img src="@/assets/Group2.png" class="temp" alt="">

        <div class="permanent">
          <div class="logo">
            <img src="@/assets/Group1.png" alt="">
            <a href="#">Enhance&nbsp;AI</a>
          </div>
    
          <div class="nav">
    
            <a href="#" class="temp-nav">Home</a>
            <a href="#" class="temp-nav">Features</a>
            <a href="#" class="temp-nav">Pricing</a>
            <a href="#" class="temp-nav">Contact</a>
            <a href="#" class="temp-nav">Login</a>
    
            <div class="signup">
              <img src="@/assets/Vector.svg" alt=""> 
              <a href="#">Free&nbsp;Signup</a>
            </div>

            <button class="menu-btn" @click="openSidebar"><i class="fa fa-bars" aria-hidden="true"></i></button>

          </div>
        </div>
      
        <img src="@/assets/Group4.png" class="temp" alt="">

    </div>

  <div class="side-bar" :class="{ active: isSidebarActive }">
      <div class="close-btn" @click="closeSidebar">
          <i class="fas fa-times"></i>
      </div>
      <div class="menu">
          <div class="item"><a href="#"><i class="fa fa-home" aria-hidden="true"></i> Home </a></div>
          <div class="item"><a href="#"><i class="fa fa-asterisk" aria-hidden="true"></i> Features </a></div>
          <div class="item"><a href="#"><i class="fa fa-usd" aria-hidden="true"></i> Pricing </a></div>
          <div class="item"><a href="#"><i class="fa fa-phone" aria-hidden="true"></i> Contact </a></div>
          <div class="item"><a href="#"><i class="fa fa-user" aria-hidden="true"></i> Login </a></div>
      </div>
  </div>

</div>


</template>
  
<script>
export default {
    name: 'Header',
    data() {
        return {
            isSidebarActive: false
        };
    },
    methods: {
        openSidebar() {
            this.isSidebarActive = true;
        },
        closeSidebar() {
            this.isSidebarActive = false;
        },
        scrollTo(sectionId) {
            const element = document.getElementById(sectionId);
            if (element) {
                element.scrollIntoView({
                    behavior: 'smooth'
                });
            }
        }
    }
}
</script>