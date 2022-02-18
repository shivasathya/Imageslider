<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>imageslider</title>
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="https://unpkg.com/swiper@8/swiper-bundle.min.css"/>
</head>
<body>
    <div class="container">
      <div class="swiper">
        <div class="swiper-wrapper">
          <!-- Slides -->
          <div class="swiper-slide"><img src="images/aston-martin.jpg" alt=""></div>
          <div class="swiper-slide"><img src="images/audi-rs-e-tron-gt.jpg" alt=""></div>
          <div class="swiper-slide"><img src="images/maserati-mc20.jpg" alt=""></div>
          <div class="swiper-slide"><img src="images/nio-et5.jpg" alt=""></div>
        </div>
        
        <div class="swiper-pagination"></div>
      
        
        <div class="swiper-button-prev"></div>
        <div class="swiper-button-next"></div>
      
       
        
      </div>
    </div>









   <script src="https://unpkg.com/swiper@7/swiper-bundle.min.js"></script>
   <script>
     const swiper = new Swiper('.swiper', {
       autoplay:{
       delay:3000,
       disableOnInteraction:false,
     },
      
      loop: true,
    
      
      pagination: {
        el: '.swiper-pagination',
        clickable:true,
      },
    
      
      navigation: {
        nextEl: '.swiper-button-next',
        prevEl: '.swiper-button-prev',
      },
    
      
      
     });
    </script>
</body>
</html>
