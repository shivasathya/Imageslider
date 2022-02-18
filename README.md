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
          <div class="swiper-slide"><img src="https://www.google.com/imgres?imgurl=https%3A%2F%2Fimages.unsplash.com%2Fphoto-1605559424843-9e4c228bf1c2%3Fixlib%3Drb-1.2.1%26ixid%3DMnwxMjA3fDB8MHxzZWFyY2h8OXx8Y2Fyc3xlbnwwfHwwfHw%253D%26w%3D1000%26q%3D80&imgrefurl=https%3A%2F%2Funsplash.com%2Fs%2Fphotos%2Fcars&tbnid=0iaHgFQXdT11jM&vet=12ahUKEwjLh4-CxYn2AhXsR2wGHRrDC-EQMygAegUIARDZAQ..i&docid=pexCxKQSr2TtXM&w=1000&h=1250&q=car%20images&ved=2ahUKEwjLh4-CxYn2AhXsR2wGHRrDC-EQMygAegUIARDZAQ" alt=""></div>
          <div class="swiper-slide"><img src="audi-rs-e-tron-gt.jpg" alt=""></div>
          <div class="swiper-slide"><img src="maserati-mc20.jpg" alt=""></div>
          <div class="swiper-slide"><img src="nio-et5.jpg" alt=""></div>
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
