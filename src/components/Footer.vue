<script setup>

</script>

<template>
  <footer class="footer">
    <div class="footer__inner">
      <a href="#" class="logo">
        <img src="src\components\images\Logo.png" alt="Логотип">
      </a>
      <nav class="menu">
        <ul class="menu__list">
          <li class="menu__list-item block1"><a class="head__submenu" href="#">Service</a>
                    <ul class="submenu__list">
			            <li class="submenu__list-item"><a href="#">Personal</a></li>
			            <li class="submenu__list-item"><a href="#">Business</a></li>
			            <li class="submenu__list-item"><a href="#">Enterprise</a></li>
                    </ul>
          </li>
          <li class="menu__list-item block2"><a class="head__submenu" href="#">API</a>
                    <ul class="submenu__list">
			            <li class="submenu__list-item"><a href="#">Developer contact</a></li>
			            <li class="submenu__list-item"><a href="#">Documentation</a></li>
			        </ul>
          </li>
          <li class="menu__list-item block3"><a class="head__submenu" href="#">Company</a>
                    <ul class="submenu__list">
			            <li class="submenu__list-item"><a href="#">About us</a></li>
			            <li class="submenu__list-item"><a href="#">Careers</a></li>
			            <li class="submenu__list-item"><a href="#">Investors</a></li>
                      
			        </ul>
          </li>
        </ul>
      </nav>
      <div class="contacts">
        <a class="contacts__in" href="#"> 
            <img src="src\components\images\instagram.png" alt="">
        </a>
        <a class="contacts__lin" href="#">
            <img src="src\components\images\linkedin.png" alt="">
        </a>
        <a class="contacts__twit" href="#">
            <img src="src\components\images\twitter.png" alt="">
        </a>
      </div>
    </div>
</footer>
  
</template>



<style scoped>

.footer{
    max-width: 1512px;
    border: 2px solid #000000;
    margin: 100px auto 50px auto;
}

.footer__inner{
    display: flex;
    justify-content: space-between;
    align-items:center;
    padding: 52px 81px 48px 62px;
    background-color: #FFFFFF;
}

.menu__list{
    display: flex;
    justify-content: space-between;      
}

.head__submenu{
    font-family: 'IBM Plex Mono';
    font-weight: 700;
    font-size: 24px;
    line-height: 87%;
    letter-spacing: -0.04em;
}

.menu__list-item, 
.submenu__list-item,
 a{
    text-decoration: none;
    list-style-type: none;
    cursor:default;
    color:#000000;
}

.submenu__list{
    padding-top: 15px;
}

.submenu__list-item{
padding-top: 8px;
font-family: 'IBM Plex Mono';
font-weight: 400;
font-size: 16px;
line-height: 87%;
letter-spacing: -0.04em;
}

.block1,
.block2{
    padding-right: 64px;
}

.contacts__in{
   padding-right: 40px;
}

.contacts__lin{
   padding-right: 40px;
}








/* .header {
  margin: 60px 71px 80px 63px;
}
  .header__inner{
    box-sizing: border-box;
    display: flex;
    justify-content: space-between;
    max-width: 1512px;
    align-items: center;
    margin: auto;
  }

  .logo{
    cursor: default;
  }

  .menu {
    max-width: 718px;
  }

.menu__list{
  display: flex;
  justify-content: space-between;
}

.menu__list-item{
  list-style: none;
  cursor: pointer;
}

li img{
  padding-left: 10px;
}

a{
  text-decoration: none;
  color: black;
}

.item1{
  padding-right: 83.5px;
}

.item2{
  padding-right: 76px;
}

.item3{
  padding-right: 72px;
}

.item4{
  padding-right: 45.5px;
}

.drop{
  padding: 20px 50px;
  background-color: white;
  position: absolute;
  margin-left: -40px;
  border: 1px solid black;
  display: none;
}
 .dropmenu {
  background-color: white;
  list-style: none;
  text-align: center;
  padding-top: 5px;
}

.dropmenu a {
background-color: white;
}
.item1:hover .drop{
display: block;
} 

.item2:hover .drop{
display: block;
} 

.item3:hover .drop{
display: block;
}  */
</style>
