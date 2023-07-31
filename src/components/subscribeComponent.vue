<template>
      <div class="subscribeComponent">
                   
         <div class="container">
         <h1>Subscribe to our Newsletter</h1>
    <form class="subscribe-form" action="#" method="post">
      <label for="email"></label>
      <input type="email" id="email" name="email" placeholder="Your email address" required>
      <input type="submit" value="Subscribe">
    </form>
  </div>
      </div>
</template>
<style>    
    .container {
        display: flex;
        flex-direction: column;
        align-items: center;
        gap: 4em;
      max-width: 80%;
      margin: 50px auto;
      background: #357fbe;
      box-shadow:  10px 10px 10px 20px gray;
      padding: 20px;
      border-radius: 5px;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    }
    
    h1 {
        font-size: 3em;
        display: flex;
        align-items: center;
        justify-content: center;
    }
    
 .subscribe-form {
align-items: center;
gap: 3em;
display: flex;
justify-content: center;
}
.subscribe-form label {
margin-bottom: 5px;
}
    
.subscribe-form input[type="email"] {
      padding-right: 70px;
      padding-left: 15px;
      padding-block: 15px;
      font-size: 1em;
      color: rgb(0, 0, 0);
      font-weight: 700;
      border: 1px solid #ccc;
      border-radius: 10px;
      margin-bottom: 10px;
    }
    
    .subscribe-form input[type="submit"] {
        margin-top: -10px;
        font-size: 1em;
      padding-inline: 20px;
      padding-block: 15px;
      background-color: #006594;
      color: #ffffff;
      border: none;
      border-radius: 10px;
      cursor: pointer;
    }
    
    .subscribe-form input[type="submit"]:hover {
      background-color: #00f7ff;
    }

</style>