 <template>
          <div class="info-component">
               <span class="card">
                           <img src="/src/assets/icons/credit-card.svg">
                           <div class="text">
                                    <h2>Secure Payment</h2>
                                    <p>
                                         Secure on Order
                                    </p>
                           </div>
               </span>

               <span class="card">
                           <img src="/src/assets/icons/delivery-truck.svg">
                           <div class="text">
                                    <h2>Fast delivery</h2>
                                    <p>
                                         Fast delivery  on order
                                    </p>
                           </div>
               </span>

               <span class="card">
                           <img src="/src/assets/icons/support.svg">
                           <div class="text">
                                    <h2>24/7 support</h2>
                                    <p>
                                         Contact us 24 hrs  a day
                                    </p>
                           </div>
               </span>
          </div>

 </template>

 <style lang="scss">
.info-component{
align-items: center;
margin-top: 5em;
grid-template-columns: repeat(auto-fit, minmax(500px, 1fr));
 display: grid;
 gap: 1rem;
 justify-content: space-around;
 .card{
  display: flex;
  gap: 2em;
 align-items: center;
  h2{
 font-weight: 600;
 font-size: 2em;     
 margin-bottom: 0.2em;
 }
 img{
  
background-color: rgb(180, 180, 180);
 border-radius: 12px;
 padding: 0.5em;
 height: 5em;

                   }
              }
            
          }






</style>