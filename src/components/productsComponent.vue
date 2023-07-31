<template>
       <article class="productsComponent">
                         <h1>
                               Popular <span>Products</span>
                         </h1>
                           <span class="products"> 
                                         <!--card-1-->
 <div class="card"> 
              <div class="like-button">
                      <img src="/src/assets/icons/heart.svg">
                </div>     
                  <div class="shoes"><img class="shoes" src="/src/assets/img/PngItem_1944356.png"></div>
               <span>
                <div class="review"><img class="star" src="/src/assets/icons/star.svg" >(4.5)</div>
                   <h3>Nike Air Jordan-100</h3>
                  <div>$80.00 <button>Add to card</button></div>
              </span>
</div> 
                               <!--card-2-->
                               <div class="card">
                                <div class="like-button">
                                                        <img src="/src/assets/icons/heart.svg">
                                                  </div>
                                <div class="shoes"><img class="shoes" src="/src/assets/img/PngItem_2441555.png"></div>
                                                  <span>
                                                    <div class="review"><img class="star" src="/src/assets/icons/star.svg" >(4.5)</div>
                                                      <h3>Nike Air Jordan-100</h3>
                                                       <div>$80.00 <button>Add to card</button></div>
                                                  </span>
                                                 
                               </div>  
                                    <!--card-3-->
                               <div class="card">
                                <div class="like-button">
                                                        <img src="/src/assets/icons/heart.svg">
                                                  </div>
                                <div class="shoes"><img class="shoes" src="/src/assets/img/PngItem_2441597.png"></div>
                                                  <span>
                                                    <div class="review"><img class="star" src="/src/assets/icons/star.svg" >(4.5)</div>
                                                      <h3>Nike Air Jordan-100</h3>
                                                       <div>$80.00 <button>Add to card</button></div>
                                                  </span>

                               </div>  
                                      <!--card-4-->
                               <div class="card">
                                <div class="like-button">
                                                        <img src="/src/assets/icons/heart.svg">
                                                  </div>
                                <div class="shoes"><img class="shoes" src="/src/assets/img/PngItem_2441637.png"></div>
                                                  <span>
                                                    <div class="review"><img class="star" src="/src/assets/icons/star.svg" >(4.5)</div>
                                                      <h3>Nike Air Jordan-100</h3>
                                                       <div>$80.00 <button>Add to card</button></div>
                                                  </span>
                               </div>  
                                      
                                        <!--card-5-->
                               <div class="card">
                                <div class="like-button">
                                                        <img src="/src/assets/icons/heart.svg">
                                                  </div>
                                <div class="shoes"><img class="shoes" src="/src/assets/img/PngItem_2441834.png"></div>
                                                  <span>
                                                    <div class="review"><img class="star" src="/src/assets/icons/star.svg" >(4.5)</div>
                                                      <h3>Nike Air Jordan-100</h3>
                                                       <div>$80.00 <button>Add to card</button></div>
                                                  </span>
                               </div>  

                                   <!--card-6-->
                               <div class="card">
                                <div class="like-button">
                                                        <img src="/src/assets/icons/heart.svg">
                                                  </div>
                                <div class="shoes"><img class="shoes" src="/src/assets/img/PngItem_390898.png"></div>
                                                  <span>
                                                    <div class="review"><img class="star" src="/src/assets/icons/star.svg" >(4.5)</div>
                                                      <h3>Nike Air Jordan-100</h3>
                                                       <div>$80.00 <button>Add to card</button></div>
                                                  </span>
                               </div>  
                                         <!--card-7-->
                               <div class="card">
                                <div class="like-button">
                                                        <img src="/src/assets/icons/heart.svg">
                                                  </div>
                                <div class="shoes"><img class="shoes" src="/src/assets/img/PngItem_4744643.png"></div>
                                                  <span>
                                                    <div class="review"><img class="star" src="/src/assets/icons/star.svg" >(4.5)</div>
                                                      <h3>Nike Air Jordan-100</h3>
                                                       <div>$80.00 <button>Add to card</button></div>
                                                  </span>
                               </div>  
                                              <!--card-8-->
                               <div class="card">
                                <div class="like-button">
                                                        <img src="/src/assets/icons/heart.svg">
                                                  </div>
                                <div class="shoes"><img class="shoes" src="/src/assets/img/PngItem_5550642.png"></div>
                                                  <span>
                                                    <div class="review"><img class="star" src="/src/assets/icons/star.svg" >(4.5)</div>
                                                      <h3>Nike Air Jordan-100</h3>
                                                       <div>$80.00 <button>Add to card</button></div>
                                                  </span>
                                                </div>
                           </span>
                           <a href="#" class="see-all">
                                  see all  <img src="/src/assets/icons/right-arrow.svg"  class=".arrow">
                           </a>
        </article>

</template>
<style lang="scss">
  .productsComponent{ 
 font-weight: 600;
 box-sizing: border-box;
  color: aliceblue;
  padding-inline: 3rem;
 padding-block: 6.32rem;
  .see-all{
display: flex;
 justify-content: center;
 align-items: center;
color: aliceblue;
font-size: 20px;
 margin-top: 3em;
img{
 height: 2em;
 }  }
 h1{
  font-size: 3rem;
  margin-bottom: 1.5em;
 font-family: 'Kanit', sans-serif;
 span{
 color: rgb(255, 81, 0);
}}
.products{
 display: grid;
 gap: 2em;
grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  .card{
border-radius:  10px 10px 10px 10px;
 background: #8a8a8a;
display: grid;
width: 20em;
grid-template-columns:  1fr;
 gap: 4em;
span{
 padding-block:  1em;
padding-inline: 1em;
gap: 3px;
 h3{
font-size: 20px;
}
 display: flex;
flex-direction: column;
button{
margin-left: 1em;
background: #0890b9;
border: none;
border-radius: 7px;
 color: aliceblue;
 font-size: 1em;
 font-weight: 600;
padding-block: 0.5em;
 padding-inline: 1em;
 }
.review{
display: flex;
align-items: center;
gap: 0.2em;
  }}                
.shoes{
display: flex;
justify-content: center;
align-items: center;
padding-block:  1em;
padding-inline: 1em;
 border-radius:  10px 10px 0px 0px ;
background: rgb(48,122,148);
 background: linear-gradient(90deg,
 rgba(48,122,148,1) 0%, 
 rgba(75,86,89,1) 42%,
 rgba(110,59,0,1) 100%,
rgba(255,85,0,1) 100%,
 rgba(2,169,227,1) 100%);
img{
height: 180px;
object-fit: cover;
 transform: rotate(-27deg);
padding-bottom: 3rem;
 background: none; }  }
 .like-button{
background-color: #0890b9;
border: rgb(255, 72, 0) 1px solid;
 margin-left: 5px;
margin-top: 5px;
border-radius: 100%;
padding: 4px;
 position: absolute;
align-items: start;
 justify-content: start;
 img{ 
display: flex;
 height: 2rem;
 } }
 .star{
height: 1.5em;}}}}
</style>