<template>
 
  <body>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin="">
    <link href="https://fonts.googleapis.com/css2?family=Source+Serif+4:wght@400;600&amp;family=IBM+Plex+Mono:wght@500&amp;display=block" rel="stylesheet">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin="">
<link href="https://fonts.googleapis.com/css2?family=Source+Serif+4:wght@400;600&amp;family=IBM+Plex+Mono:wght@500&amp;display=block" rel="stylesheet">

    <div class="container">
    <div class="navbar">
      <img src="../src/assets/dribble-logo.png" class="imagedr">
      <nav class="header">
        <ul class="header_ul">
          <li class="header_li">
            <a href="#" class="a_li">Find Talent</a>
          </li>
          <li class="header_li">
            <a href="#" class="a_li">For designer</a>
          </li>
          <li class="header_li">
            <a href="#" class="a_li">Inspiration</a>
          </li>
          <li class="header_li">
            <a href="#" class="a_li">Learn Design</a>
          </li>
          <li class="header_li">
            <a href="#" class="a_li">Go Pro</a>
          </li>
        </ul>
      
      </nav>
      <div class="button">
        <a href="#" class="Login">Log in</a>
        <a href="#" class="sign">Sign Up</a>
      </div>
      </div>
      <div class="main">
        <video class="bgvideo" autoplay muted loop >
        <source src="../src/assets/dribbleVideo.mp4">
      </video>

      <header class="hoverbutton">
      <ul class="hover_ul">
        <li class="blur-btn"><a class="category" href="#">Discover</a></li>
  <li class="blur-btn"><a class="category" href="#">Animation</a></li>
  <li class="blur-btn"><a class="category" href="#">Branding</a></li>
  <li class="blur-btn"><a class="category" href="#">Illustration</a></li>
  <li class="blur-btn"><a class="category" href="#">Mobile</a></li>
  <li class="blur-btn"><a class="category" href="#">Print</a></li>
  <li class="blur-btn"><a class="category" href="#">Product Design</a></li>
  <li class="blur-btn"><a class="category" href="#">Typography</a></li>
  <li class="blur-btn"><a class="category" href="#">Web Design</a></li>
        </ul>
        <div class="contents">
          <h1>Explore the world’s leading design portfolios</h1>
        </div>

          <p class="contents-para">Millions of designers and agencies around the world showcase their portfolio work on Dribbble - the home to the world’s best design and creative professionals.</p>
          <input id="search" type="search" name="q" placeholder="Search..." value="" class="search-input js-search-input">
          
          <footer>
    <div class="foot">
      <p class="text">Trending searches</p>
    
    <ul class="hoverdown_ul">
        <li class="blur-btn"><a class="category-2" href="#">landing page</a></li>
  <li class="blur-btn"><a class="category-2" href="#">ios</a></li>
  <li class="blur-btn"><a class="category-2" href="#">food</a></li>
  <li class="blur-btn"><a class="category-2" href="#">landingpage</a></li>
  <li class="blur-btn"><a class="category-2" href="#">uxdesign</a></li>
  <li class="blur-btn"><a class="category-2" href="#">appdesign</a></li>
  </ul>
</div>
  </footer>
      </header>
 
      </div>
      </div>
  </body>
</template>

<style scoped>
*,
*::after,
*::before{
  margin: 0;
  padding: 0;
  box-sizing: inherit;
}
.text{
  color: #FFFFFF;
  
}


body{
  box-sizing: border-box;
  font-family: "Haas Grot Text R Web", "Helvetica Neue", Helvetica, Arial, sans-serif;
  font-size: 16px;
  font-weight: 500;
  
}
.foot{
  display: flex;
  align-items: center;
  white-space: nowrap;
  margin-top: 15px;
}
.navbar{
  display: flex;
  align-items: center;
  height: 100px;
  background-color: #FFFFFF;
  padding-left:24px ;
  padding-right: 24px;
}
.header_ul{
  list-style: none;
  display: flex;
  gap: 24px;
}
.a_li{
  color: #0D0C22;
  text-decoration: none;
  letter-spacing: .5px;
}
.header{
  display: flex;
  align-items: center;
  width: -webkit-fill-available;
  
  padding-left: 46px;


}
.imagedr{
  height: inherit;

}
.button{
  display: flex;
  align-items: center;
    gap: 35px;
  white-space: nowrap;
}
.Login{
  text-decoration: none;
  color: #0D0C22;
}
.sign{
  text-decoration: none;
  background-color: #0D0C22;
  color: #FFFFFF;
  height: 50px;
  text-align: center;
  padding: 0 16px;
  border-radius: 8px;
  display: flex;
  align-items: center;
}
.main{
  height: 100vh;
  max-width: 100vw;
  position: relative;

  display: grid;
  grid-template-columns: repeat(8,1fr);
  
}
.bgvideo{
  width: 100%;
  height: 100%;
  object-fit: cover;
  position: absolute;
}
.hoverbutton
{
  grid-column: 3/7;
  position:absolute;
  display: flex;
  justify-content: center;
  align-items: center;
  width: -webkit-fill-available;

  flex-direction: column;

}
.hover_ul{
    display: flex;
    gap: 24px;
    list-style: none;
    align-content: center;
    justify-content: center;
    padding: 12px 60px;
}
.hoverdown_ul{
    display: flex;
    gap: 10px;
    list-style: none;
    align-content: center;
    justify-content: center;
    padding: 12px 60px;
}
.category{
    display: inline-block;
    text-decoration: none;
    color: #FFFFFF;
    background: rgba(0, 0, 0, .5);
    height: auto;
    padding: 16px 20px;
    border-radius: 50px;
    white-space: nowrap;
    transition: all .2s ease-in;
  
}
.category-2{
    display: inline-block;
    text-decoration: none;
    color: #FFFFFF;
    background: rgba(0, 0, 0, .5);
    height: auto;
    padding: 4px 10px;
    border-radius: 50px;
    white-space: nowrap;
    transition: all .2s ease-in;
  
}
.category:hover{
  background-color: #FFFFFF;
  color: black;
}

.contents{
  margin-top: 50px;
  display: flex;
  grid-column: 4/6;
  flex-direction: column;
  color: #FFFFFF;
  margin-top: 6px;
  padding: 1px 63px;

  text-align: center;
  gap: 40px;
  font-family:"Haas Grot Text R Web", "Helvetica Neue", Helvetica, Arial, sans-serif ;
}
.search-input,
.search-input:focus
{
  padding: 16px 273px 25px 55px;
    border-radius: 50px;
    border: none;
    margin-top: 30px;

}
.contents-para{

  color: #FFFFFF;
  margin-top: 20px;
}
</style>