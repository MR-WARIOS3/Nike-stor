<template>
      <div class="footerComponent">
              <img  class="logo-2" src="/src/assets/icons/nike.svg" alt="">
                      <ul class="items">
                                   <li class="item">
                                      <h3 href="#">About</h3>
                                      <a href="#">About us</a>
                                      <a href="#">features</a>
                                      <a href="#">News & Blogs</a>
                                   </li>

                                   <li class="item">
                                      <h3 href="#">Contact</h3>
                                      <a href="#">Linkdin</a>
                                      <a href="#">Instagram</a>
                                      <a href="#">Twitter</a>
                                   </li>

                                   <li class="item">
                                      <h3 href="#">Support</h3>
                                      <a href="#">FAQs</a>
                                      <a href="#">Support Center</a>
                                      <a href="#">Contact us</a>
                                   </li>
                      </ul>

      </div>

</template>
<style >

.footerComponent{
    background-color: aliceblue;
    margin-top: 8em;
    justify-content: space-around;
      display: flex;
      align-items: center;
}
h3{
     font-size: 1.5em;
     font-weight: 700;
}
.items{
     display: flex;
     gap: 5em;
}
.item{
     display: flex;
     gap: 1em;
     color: rgb(67, 67, 68);
     flex-direction: column;
}
.item a{
     color: rgb(0, 0, 0);
}
.item a::after{
                                   content: '';
                                   display: block;
                                   width: 0;
                                   height: 2px;
                                    background: #000;
                                   transition: width .3s;
                            }
                            .item a:hover::after{
                                   width: 100%;
                            }
      .logo-2{
        height: 15rem;
      }


</style>