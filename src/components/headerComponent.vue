<template>
  <nav class="navbar">
    <!-- LOGO -->
    <div class="logo">
         <img src="/src/assets/icons/nike.svg"  class="w-16">
    </div>

    <!-- NAVIGATION MENU -->
    <ul class="nav-links">

      <!-- USING CHECKBOX HACK -->
      <input type="checkbox" id="checkbox_toggle" />
      <label for="checkbox_toggle" class="hamburger">&#9776;</label>

      <!-- NAVIGATION MENUS -->
      <div class="menu">

        <li><a href="/">Men</a></li>
        <li><a href="/">Women</a></li>
        <li class="/">Kids</li>
        <li><a href="/">FAQs</a></li>
        <li><a href="/">Contact</a></li>
       <div>
           <img src="/src/assets/icons/cart.svg" class="w-10 ml-28">
       </div>
      </div> 

    </ul>

  </nav>
</template>
<style>
.navbar {
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding-inline: 3rem;
  padding-block: 1.5rem;
  color: #fff;
}

.nav-links a {
  color: #fff;
}

/* LOGO */
.logo {
  font-size: 32px;
}

/* NAVBAR MENU */
.menu {
  display: flex;
  gap: 1em;
  font-size: 18px;
}

.menu li:hover {
  background-color: #4c9e9e;
  border-radius: 5px;
  transition: 0.3s ease;
}

.menu li {
  padding: 5px 14px;
}

/* DROPDOWN MENU */
.services {
  position: relative; 
}

.dropdown {
  padding: 1em 0;
  position: absolute; /*WITH RESPECT TO PARENT*/
  display: none;
  border-radius: 8px;
  top: 35px;
}

.dropdown li + li {
  margin-top: 10px;
}

.dropdown li {
  padding: 0.5em 1em;
  width: 8em;
  text-align: center;
}

.dropdown li:hover {
  background-color: #4c9e9e;
}

.services:hover .dropdown {
  display: block;
}
input[type=checkbox] {
  display: none;
} 

/* HAMBURGER MENU */
.hamburger {
  display: none;
  font-size: 24px;
  user-select: none;
}

/* APPLYING MEDIA QUERIES */
@media (max-width: 768px) {
 .menu {
    display:none;
    position: absolute;
    right: 0;
    left: 0;
    text-align: center;
    padding: 16px 0;
  }

  .menu li:hover {
    display: inline-block;
    background-color:#4c9e9e;
    transition: 0.3s ease;
  }

  .menu li + li {
    margin-top: 12px;
  }

  input[type=checkbox]:checked ~ .menu {
    display: block;
  }

  .hamburger {
    display: block;
  }

  .dropdown {
    left: 50%;
    top: 30px;
    transform: translateX(35%);
  }

  .dropdown li:hover {
    background-color: #4c9e9e;
  }
}

</style>