<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header >
        <h1> Muhammad Usman</h1>
        <p>My name is Muhammad Usman. I am a software engineering student, 
            and I aim to develop a strong grip on web development in the future. 
            I hope that I will learn a lot from the University of Lahore.</p>
    </header>

    <div class="About-Me">
       <h2>About Me</h2>
        <p>My name is Muhammad Usman. I am a software engineering student, 
            and I aim to develop a strong grip on web development in the future. 
            I hope that I will learn a lot from the University of Lahore.</p>
    </div>

    <div class="Projects">
       <!-- <h2>Portfolio</h2> -->
        <div class="Projects1">
            <img src="images.jfif" alt="My Shopify Store" width="98%" height="200" title="University of Lahore">
            <a href="https://sufiebrand.myshopify.com/" target="_blank"> Click to Visit My Store</a>
        </div>
        <div class="Projects2">
            <img src="download.jfif" alt="University of Lahore" width="98%"  height="200" title="University of Lahore">
            <a href="https://www.facebook.com/sufyybrand/" target="_blank">Visit My Page </a>
        </div>
        <div class="Projects3">
            <img src="whatsapp.jfif" alt="University of Lahore" width="98%" height="200" title="University of Lahore" >
            <a href="https://api.whatsapp.com/send?phone=923001726944" target="_blank">Visit My Business Account</a>
        </div>
    </div>

    <div class="form"> 
  <form action="">
    <h5 style="text-align: center;">Enquiry Form</h5>
  
        <label form=""><b>Name</b></label><br>
        <input type="text" placeholder="Enter your name">
        
        
        <br>
        <label form=""><b>Email </b></label>
        <br>
        <input type="email" placeholder="Enter your email">
       
        
        <br>
        <label form="">Gender</label><br>
        <input type="gender" placeholder="Male/Female">
        
        <br>
        <label form="">Phone</label><br>
        <input type="tel" pattern="[0-9]{11}" placeholder="Enter your number">
        
        <br>
        <label form="">Age</label><br>
        <input type="number" placeholder="Enter your age">
        
        <br>     
        <label form="hobbies">Hobbies:</label><br>
        <input list="hobby-options"  name="hobbies" placeholder="Type or select a hobby">    
        <datalist id="hobby-options">
          <option value="Playing">
          <option value="Traveling">
          <option value="Music">
          <option value="Cooking">
          <option value="Photography">
          <option value="Gardening">
          <option value="Painting">
          <option value="Writing">
        </datalist>   
     <br>
       
        <label for="Adress">Adress</label><br>
        <input list="Adress"  name="Adress" placeholder="Type or select a Adress">    
        <datalist id="Adress">
          <option value="Lahore">
          <option value="Gujranwala">
          <option value="Faislabad">
          <option value="Pindi Bhattian">
          <option value="Muree">
          <option value="Sawat">
          <option value="Naran Kaghan">
          <option value="Babusar Top">
        </datalist>   
        <br>
        <button type="submit" >Save and Submit</button>
        <br>      
  </form>
</div>
<footer>
    <p>Follow Us:</p>
    <div class="social-buttons">
        <!-- Facebook Button -->
        <a href="https://www.facebook.com" target="_blank">
            <img src="https://upload.wikimedia.org/wikipedia/commons/5/51/Facebook_f_logo_%282019%29.svg" alt="Facebook">
        </a>

       

        <!-- Instagram Button -->
        <a href="https://www.instagram.com" target="_blank">
            <img src="https://upload.wikimedia.org/wikipedia/commons/a/a5/Instagram_icon.png" alt="Instagram">
        </a>
    </div>
</footer>



</body>
</html>
