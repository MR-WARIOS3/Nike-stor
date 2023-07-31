<template>
       <article class="articleComponent">
                <div class="article-img">
                      <img src="/src/assets/img/article-img.png">
                </div>
                <div class="article-text">
                          <h1>Dedicated to <br>quality and result</h1>
                           <p>
providing the best shoe of various types and manufacturing
them for true travel lovers. these items are lightweight and
comfortable.
                           </p>
                           <button>
                              Read more
                           </button>
                </div>
       </article>



</template>
<style lang="scss">
          .articleComponent{
                      padding-block: 9rem;
                      padding-inline: 3rem;
                      width: 100%;
                      
                      gap: 4em;
                     display: grid;
                     grid-template-columns: repeat(auto-fit, minmax(500px, 1fr));


                       .article-img img{
                             height: 16rem;
                             width: auto;
                             transform: rotate(19deg);
                       }
                  .article-text{
                        
                         font-weight:  600; 
                         gap: 12px;
                                h1{
                                     font-size: 4rem;
                                     font-family: 'Kanit', sans-serif;
                                }
                                  p{
                                     font-size: 1.3rem;
                                     margin-bottom:10px;
                                  }
                                  button{
                                    color: aliceblue;
                                    font-size: 1.3em;
                                    font-weight: bold;
                                    border-radius: 12px;
                                      border: none;
                                      background-color: rgb(36, 175, 255);
                                      padding-inline: 19px;
                                      padding-block: 15px;
                                  }
                  }



          }
          @media (max-width: 768px) {
               .articleComponent{
                         img{
                               height: 20rem;
                         }
               }
          }


</style>