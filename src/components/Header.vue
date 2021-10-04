<template>
  <header class="header">
    <img class="logo" src="../assets/img/omnifood-logo.png" alt="Omnifood logo">
    <nav class="main-nav">
      <ul class="main-nav-list">
        <li><a class="main-nav-link" href="#">Section 1</a></li>
        <li><a class="main-nav-link" href="#">Section 2</a></li>
        <li><a class="main-nav-link" href="#">Section 3</a></li>
        <li><a class="main-nav-link" href="#">Section 4</a></li>
        <li><a class="main-nav-link nav-cta" href="#">Section 5</a></li>
      </ul>
    </nav>
  </header>
</template>
<style>
.header{
  display: flex;
  justify-content: space-between;
  align-items: center;
  background-color: #fdf2e9;
  height: 9.6rem;
  padding: 0 4.8rem;
}
.logo{
  height: 2.2rem;
}
.main-nav-list{
  list-style: none;
  display: flex;
  align-items: center;
  gap: 3.2rem;
}
.main-nav-link:link, 
.main-nav-link:visited{
  display: inline-block;
  text-decoration: none;
  color: #333;
  font-weight: 500;
  font-size: 1.8rem;
  transition: all 0.3s;
}
.main-nav-link:hover,
.main-nav-link:active{
  color: #cf711f;
}
.main-nav-link.nav-cta:link, 
.main-nav-link.nav-cta:visited{
  padding: 1.2rem 2.4rem;
  border-radius: 9px;
  color: #fff;
  background-color: #e67e22;
}
.main-nav-link.nav-cta:hover, 
.main-nav-link.nav-cta:active{
  background-color: #cf711f;
}
</style>