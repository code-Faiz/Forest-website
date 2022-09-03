<template>
  <div id="app">

    <section class="header">
      <nav>
        <!-- <a href="index.html"><img src=""></a> -->
        <div class="nav-bar">
          <ul>
            <li><a href="">HOME</a></li>
            <li><a href="">ABOUT</a></li>
            <li><a href="">CATEGORY</a></li>
            <li><a href="">BLOG</a></li>
            <li><a href="">GALLERY</a></li>
          </ul>  
        </div>
      </nav>

      <div class="textbox">
        <h1>F O R E S T</h1>
      </div>
    </section>


    <!--     About     -->

    <section class="about">
     <div class="aboutcontain">
      <img src="./image/about.png" class="aboutimg">
     </div>

     <div class="abouttext">
      <p>A forest is a complex ecological system in which trees are the dominant life-form. A forest is nature’s most efficient ecosystem, with a high rate of photosynthesis affecting both plant and animal systems in a series of complex organic relationships. Forests can develop under various conditions, and the kind of soil, plant, and animal life differs according to the extremes of environmental influences.</p>
        
      <p>There are three main types of forests, defined by latitude: taiga (boreal) forests, temperate forests, and tropical forests.</p>
        
      <p>Forests are distinguished from each other according to species composition (which develops in part according to the age of the forest), the density of tree cover, soil types, and the geologic history of the forest region.</p>
        
      <p> Tree-dominated forests can occur where the temperature rises to above 10 °C (50 °F) in the warmest months, and the annual precipitation is more than 200 mm (8 inches).</p>
      
     </div>
    </section>

    
  </div>
</template>

<script>


export default {
  name: 'App',
  
}
</script>

<style>

@import url(//db.onlinewebfonts.com/c/55d433372d270829c51e2577a78ef12d?family=Monument+Extended);

  *{
    margin: 0;
    padding: 0;
  }

  .header{
    min-height: 100vh;
    width: 100%;
    background-image: url(image/bg.jpg);
    background-position: center;
    background-size: cover;
    position: relative;

  }

  nav{
    display: flex;
    padding: 2% 35%;
    justify-content: space-between;
    align-items: center;
  }

  nav img{
    width: 150px;
  }

  .nav-bar{
    flex: 1;
    text-align: right;
  }

  nav ul li{
    list-style: none;
    display: inline;
    padding: 8px 12px;
    position: relative;
  }

  .nav-bar ul li a{
    color: #fff;
    text-decoration: none;
    font-size: 13px;
    font-family: "Monument Extended"; 

  }

  .textbox{
    width: 90%;
    color: #fff;
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    text-align: center;
    font-size: 90px;
    font-family: "Monument Extended"; 
    
  }

  .about{
    width: 100%;
    margin: auto;
    padding-top: 80px;
  }

  .aboutcontain{
    width: 90%;
    position: absolute;
    left:5%;
    text-align: center;
    align-item:center;
  }

  .aboutimg{
    width:800px;
  }

  .abouttext{
    background-color: rgb(45, 152, 102);
    width: 1200px;
    height: 200px;
    position:relative;
    left:10%;
    top: 40vh;
    color:white;
    text-align: justify;
    border-radius:20px;
  }

  .abouttext p{
    position:relative;
    top: 20%;
    font-size:15px;
    margin-left: 1%;
    margin-right: 1%;
  }

  

</style>
