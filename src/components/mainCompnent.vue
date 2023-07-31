<template>
          <main class="mainComponent">
                      <div class="main-text">
                            <h1>
                                     Comfort & <br>
                                      Magic Awaits. <br>
                                      Everyday.
                            </h1>
                            <div class="review-shop">
                              <a href="#" class="shop">
                                  Shop Now
                             </a>
                              <span>
                                         <div class="review"> 
                                                  4.9
                                                 <div class="stars">
                                                         <img src="/src/assets/icons/star.svg">
                                                         <img src="/src/assets/icons/star.svg">
                                                         <img src="/src/assets/icons/star.svg">
                                                         <img src="/src/assets/icons/star.svg">
                                                         <img src="/src/assets/icons/star.svg">
                                                 </div>
                                         </div>
                                         <h3>120K TUTAl REVIEW</h3>
                              </span>
                            </div>

                      </div>
                      <div class="shoes">
                             <img  src="/src/assets/img/PngItem_109181.png" >
                      </div>
          </main>
 
</template>
<style lang="scss">
.mainComponent{
padding-top: 5rem;
display: flex;
 justify-content: space-around;
align-items: center;
.shoes{
        width: auto;
 background-size: cover;
backdrop-filter: blur(5px);
background: rgb(255,106,0);
background: radial-gradient(circle, rgba(255,106,0,1) 0%, rgba(255,115,0,1) 55%, rgba(255,0,0,1) 100%);
border: rgb(107, 107, 107) solid 3px;
border-radius: 100%;
position: relative;
background-position: center;
background-repeat: no-repeat;
background-size: cover;
}
.main-text{
h1{
font-size: 5rem;
font-family: 'Kanit', sans-serif;
}
 .review-shop{
display: flex;
 gap: 3em;
 align-items: center;
 .review{
  display: flex;
 gap: 6px;
 align-items: center;
 margin-bottom: 5px;
}     
.stars{
gap: 3px;
padding-left: 5px;
 display: flex;
border-left: solid black  2px;
img{
height: 1.6em;
} }}
 .shop{
border-radius: 12px;
color: aliceblue;
font-size: 1em;
font-weight: 600;
padding-block: 0.7em;
padding-inline: 2em;
border: none;
background-color: #5b9ee1;
 }}}
 @media (max-width: 768px) {
        .mainComponent{
                 text-align: center;
                flex-direction: column;
                span{
                         flex-direction: column;
                }
                     .shoes{
                         margin-top: 2em;
                         width: 25rem;
                     }
        }
 }
</style>