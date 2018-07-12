<template>
  
 <div>
      <yd-navbar title="NavBar">
        <nuxt-link to="/" slot="left">
            <yd-navbar-back-icon></yd-navbar-back-icon>
        </nuxt-link>
        <router-link to="#" slot="right">
            <yd-navbar-next-icon></yd-navbar-next-icon>
        </router-link>
    </yd-navbar>
   <yd-slider autoplay="3000">
        <yd-slider-item>
            <a href="http://www.ydcss.com">
                <img src="http://static.ydcss.com/uploads/ydui/1.jpg">
            </a>
        </yd-slider-item>
        <yd-slider-item>
            <a href="http://www.ydcss.com">
                <img src="http://static.ydcss.com/uploads/ydui/2.jpg">
            </a>
        </yd-slider-item>
        <yd-slider-item>
            <a href="http://www.ydcss.com">
                <img src="http://static.ydcss.com/uploads/ydui/3.jpg">
            </a>
        </yd-slider-item>
    </yd-slider>
 </div>
</template>

