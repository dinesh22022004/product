<?php

$con=mysqli_connect('localhost','root','','task3');
session_start();

if(mysqli_connect_error()){
    echo "<script>alert('can not connect to data base');</script>";
    exit();
}


?>

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>One Page Ad</title>
  
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz" crossorigin="anonymous"></script>
  <style>
    body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
  }

  .container {
    padding: 20px;
  }

  header img {
    max-width: 100%;
  }

  h1 {
    margin: 10px 0;
    text-align: center;
  }

  .horizontal-box {
    background-color: #f0f0f0;
    padding: 20px;
    margin-bottom: 40px;
  }

  .content {
    text-align: center;
  }

  .features {
    display: flex;
    justify-content: space-around;
    margin-bottom: 20px;
  }

  .circle {
    width: 80px;
    height: 80px;
    background: linear-gradient(45deg, #f09433 0%, #e6683c 25%, #dc2743 50%, #cc2366 75%, #bc1888 100%);
    color: #fff;
    border-radius: 50%;
    text-align: center;
    cursor: pointer;
    border: 3px solid #fff;
    position: relative;
    overflow: hidden;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
  }

  .circle img, .circle video {
    width: 500px;
    height: 100px;
    object-fit:cover;
    border-radius: 50%;
    display: none;
  }

  .circle.active img, .circle.active video {
    display: block;
  }

  .circle .add-story-icon {
    position: absolute;
    bottom: 1%;
    font-size: 18px;
    display: block;
    right: 16%;
  }

  .circle.active .add-story-icon {
    display: none;
  }

  .shop-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    gap: 20px;
    padding: 20px 0;
    
  }
 
  .shop-item {
    background-color: #f8f9fa;
    border: 1px solid #ddd;
    border-radius: 8px;
    text-align: center;
    padding: 15px;
  }

  .shop-item img {
    max-width: 100%;
    height: auto;
    border-radius: 8px;
  }

  .shop-item button {
    margin-top: 10px;
    background-color: #007bff;
    color: #fff;
    border: none;
    padding: 10px 20px;
    border-radius: 4px;
    cursor: pointer;
  }

  .shop-item button:hover {
    background-color: #0056b3;
  }

  .rectangle-box {
    width: 90%;
    background-color: #f00;
    color: #fff;
    text-align: center;
    padding: 10px;
    margin: 20px auto;
    display: flex;
    align-items: center;
    justify-content: space-between;
  }
  .rectangle-box p{
    font-size: 25px;
  }
  .shop-dropdown {
    margin-left: 10px;
    padding: 5px;
    border: none;
    border-radius: 4px;
  }

  .navbar-bottom {
    background-color: #333;
    box-shadow: 0 -4px 2px -2px gray; /* Change shadow direction */
    color: #fff;
    position: fixed;
    bottom: 0;
    left: 0;
    width: 100%;
    z-index: 1000;
    padding: 10px 0; /* Add padding */
  }

  .navbar-bottom .navbar-content {
    width: 90%; /* Adjust width */
    margin: auto;
    background-color: #f8f9fa; /* Box background color */
    border-radius: 8px; /* Add border-radius */
    padding: 10px; /* Add padding */
    display: flex;
    justify-content: space-between;
    align-items: center;
  }

  .navbar-items {
    display: flex;
    width: 100%;
    justify-content: space-around;
  }

  .navbar-bottom a {
    text-decoration: none;
    color: #333;
    padding: 8px 5px;
    border-radius: 5px;
    transition: background-color 0.3s;
    background-color: #007bff;
    color: #fff;
  }

  .navbar-bottom a:hover {
    background-color: #0056b3;
  }

  /* Modal styles */
  .modal {
    display: none;
    position: fixed;
    z-index: 1000;
    left: 0;
    top: 0;
    width: 100%;
    height: 100%;
    overflow: auto;
    background-color: rgba(0, 0, 0, 0.9);
  }

  .modal-content {
    position: relative;
    margin: auto;
    top: 0;
    width: 100%;
    height: 100%;
    display: flex;
    align-items: flex-end; /* Align items to the end (bottom) of the container */
    justify-content: center;
    flex-direction: column;
  }

  .modal-content img, .modal-content video {
    max-width: 100%;
    max-height: 80%; /* Limit height to 80% of the container */
  }

  .close {
    position: absolute;
    top: 20px;
    right: 20px;
    color: #fff;
    font-size: 40px;
    font-weight: bold;
    cursor: pointer;
  }

  .back-icon {
  position: absolute;
  top: 10px;
  left: 20px;
  color: #000;
  font-size: 40px;
  font-weight: bold;
  cursor: pointer;
  z-index:1001; /* Ensure the icon appears above the modal content */
}

.back-icon:hover {
  font-size: 50px; /* Increase size on hover */
}

.carousel-item img {
  width: 100%;
  height: 400px; /* Set a fixed height for the images */
  object-fit: cover; /* Ensure the images cover the area without distortion */
}
.carousel-caption h5, p{
    color: #000;
}

</style>
</head>
<body>
  <div class="container">
    <header>
      
      <h1>Wel-Come</h1>
    </header>
    <section class="horizontal-box">
      <div class="content">
        <h2><?php
          echo $_SESSION['taluka'];?></h2>
      </div>
    </section>
  
    <section class="features">
      <div class="circle" onclick="showStory('local')">
        <img id="local-story" src="" alt="Local Story" onclick="showFullScreen('local')">
        <video id="local-story-video" controls style="display:none" onclick="showFullScreen('local')"></video>
        <span class="add-story-icon">&#x2795;</span>
        <span>Local</span>
      </div>
      <div class="circle" onclick="showStory('area')">
        <img id="area-story" src="" alt="Area Story" onclick="showFullScreen('area')">
        <video id="area-story-video" controls style="display:none" onclick="showFullScreen('area')"></video>
        <span class="add-story-icon">&#x2795;</span>
        <span>Area</span>
      </div>
      <div class="circle" onclick="showStory('shop')">
        <img id="shop-story" src="" alt="Shop Story" onclick="showFullScreen('shop')">
        <video id="shop-story-video" controls style="display:none" onclick="showFullScreen('shop')"></video>
        <span class="add-story-icon">&#x2795;</span>
        <span>Shop</span>
      </div>
      <div class="circle" onclick="showStory('promotion')">
        <img id="promotion-story" src="" alt="Promotion Story" onclick="showFullScreen('promotion')">
        <video id="promotion-story-video" controls style="display:none" onclick="showFullScreen('promotion')"></video>
        <span class="add-story-icon">&#x2795;</span>
        <span>Promotion</span>
      </div>
    </section>
  </div>
  
  <div id="carouselExampleCaptions" class="carousel slide" data-bs-ride="carousel">
    <div class="carousel-indicators">
      <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
      <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="1" aria-label="Slide 2"></button>
      <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="2" aria-label="Slide 3"></button>
    </div>
    <div class="carousel-inner">
      <div class="carousel-item active">
        <img src="baner02.jpg" class="d-block w-100" alt="Slide 1">
        <div class="carousel-caption d-none d-md-block">
          <h5>Cloth Brand</h5>
          <p>Get the best deals now!</p>
        </div>
      </div>
      <div class="carousel-item">
        <img src="banner01.jpg" class="d-block w-100" alt="Slide 2">
        <div class="carousel-caption d-none d-md-block">
          <h5>Agri Culture</h5>
          <p>Check out our latest offers.</p>
        </div>
      </div>
      <div class="carousel-item">
        <img src="banner03.jpg" class="d-block w-100" alt="Slide 3">
        <div class="carousel-caption d-none d-md-block">
          <h5>Home appliance</h5>
          <p>Don't miss out on our special discounts.</p>
        </div>
      </div>
    </div>
    <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="prev">
      <span class="carousel-control-prev-icon" aria-hidden="true"></span>
      <span class="visually-hidden">Previous</span>
    </button>
    <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="next">
      <span class="carousel-control-next-icon" aria-hidden="true"></span>
      <span class="visually-hidden">Next</span>
    </button>
  </div>
  
  <div class="rectangle-box">
    <p>Select Shop</p>
    <select class="shop-dropdown" onchange="showShopDetails()">
      <option value="">Select Shop</option>
      <option value="shop1">Cloth</option>
      <option value="shop2">Electric</option>
      <option value="shop3">Mobile</option>
      <option value="shop4">Agri Culture</option>
    </select>
  </div>
  
  <div id="shop-items" class="shop-grid"></div>
  <br><br>
  
  <!-- Navbar at the bottom of the page -->
  <nav class="navbar-bottom">
    <div class="navbar-content">
      <div class="navbar-items">
        <a href="#">Home</a>
        <a href="#">New Product</a>
        <a href="#">News</a>
        <a href="#">New Offers</a>
      </div>
    </div>
  </nav>
  <!-- Modal for displaying full screen image/video -->
  <div id="story-modal" class="modal">
    <span class="close" onclick="closeModal()">&times;</span>
    <span class="back-icon" onclick="goBack()">&#x2190;</span> <!-- Back icon -->
    <span class="next-icon" onclick="nextStory()">&#x2192;</span> <!-- Next icon -->
    <div class="modal-content">
      <img id="modal-image" src="" alt="Story Image">
      <video id="modal-video" controls style="display:none"></video>
    </div>
  </div>
  
  
  <input type="file" id="story-input" accept="video/*,image/*" style="display:none" onchange="uploadStory(event)">
  
  <script>
    var storyImages = []; // Array to store uploaded story images
    var currentIndex = 0; // Index to keep track of the current story image

    function visitShop(shopName) {
      alert('Visiting ' + shopName);
    }
    function showShopDetails() {
      var selectElement = document.querySelector('.shop-dropdown');
      var selectedValue = selectElement.value;
      var shopItemsContainer = document.getElementById('shop-items');
      var shopDetailsContainer = document.getElementById('shop-details');

      // Clear previous content
      shopItemsContainer.innerHTML = '';
      shopDetailsContainer.innerHTML = '';

      // Shop items data
      var shopData = {
        shop1: [
          { img: 'cloths1.jpg', name: 'Cloth Shop A' },
          { img: 'cloths2.jpg', name: 'Cloth Shop B' }
        ],
        shop2: [
          { img: 'ele.jpg', name: 'Electric Shop A' },
          { img: 'electric1.jpg', name: 'Electric Shop B' }
        ],
        shop3: [
          { img: 'mobile1.jpg', name: 'Mobile Shop A' },
          { img: 'mobile2.jpg', name: 'Mobile Shop B' }
        ],
        shop4: [
          { img: 'agri1.jpg', name: 'Agri Culture Shop A' },
          { img: 'agri2.jpg', name: 'Agri Culture Shop B' }
        ]
      };

      // Display shop items based on the selected shop
      if (shopData[selectedValue]) {
        shopData[selectedValue].forEach(shop => {
          var shopItem = `
            <div class="shop-item">
              <img src="${shop.img}" alt="${shop.name}">
              <button onclick="visitShop('${shop.name}')">Visit</button>
            </div>
          `;
          shopItemsContainer.innerHTML += shopItem;
        });
        shopDetailsContainer.innerHTML = '<p>Select a shop to see details.</p>';
      } else {
        shopDetailsContainer.innerHTML = '<p>Please select a shop.</p>';
      }
    }

    function showStory(storyType) {
      var inputElement = document.getElementById('story-input');
      inputElement.setAttribute('data-story-type', storyType);
      inputElement.click();
    }

    function uploadStory(event) {
      var inputElement = event.target;
      var storyType = inputElement.getAttribute('data-story-type');
      var file = event.target.files[0];

      if (file && (file.type.startsWith('video') || file.type.startsWith('image'))) {
        var reader = new FileReader();
        reader.onload = function(e) {
          var mediaUrl = e.target.result;
          var storyImage = document.getElementById(storyType + '-story');
          var storyVideo = document.getElementById(storyType + '-story-video');

          if (file.type.startsWith('video')) {
            storyVideo.src = mediaUrl;
            storyVideo.style.display = 'block';
            storyImage.style.display = 'none';
          } else {
            storyImage.src = mediaUrl;
            storyImage.style.display = 'block';
            storyVideo.style.display = 'none';
          }

          document.querySelector('.circle[onclick="showStory(\'' + storyType + '\')"]').classList.add('active');
          alert('Story uploaded successfully!');
        };
        reader.readAsDataURL(file);
      } else {
        alert('Please upload a valid image or video file.');
      }
    }

    function showFullScreen(storyType) {
      var modal = document.getElementById('story-modal');
      var modalImage = document.getElementById('modal-image');
      var modalVideo = document.getElementById('modal-video');
      var storyImage = document.getElementById(storyType + '-story');
      var storyVideo = document.getElementById(storyType + '-story-video');

      if (storyVideo.style.display === 'block') {
        modalVideo.src = storyVideo.src;
        modalVideo.style.display = 'block';
        modalImage.style.display = 'none';
      } else {
        modalImage.src = storyImage.src;
        modalImage.style.display = 'block';
        modalVideo.style.display = 'none';
      }

      modal.style.display = 'block';
    }

    function goBack() {
      var modal = document.getElementById('story-modal');
      modal.style.display = 'none';
    }

    function closeModal() {
      var modal = document.getElementById('story-modal');
      var modalImage = document.getElementById('modal-image');
      var modalVideo = document.getElementById('modal-video');

      modal.style.display = 'none';
      modalImage.src = '';
      modalVideo.src = '';
    }

  

    function updateModalContent() {
      var modalImage = document.getElementById('modal-image');
      var modalVideo = document.getElementById('modal-video');

      if (storyImages[currentIndex].type.startsWith('video')) {
        modalVideo.src = storyImages[currentIndex].url;
        modalVideo.style.display = 'block';
        modalImage.style.display = 'none';
      } else {
        modalImage.src = storyImages[currentIndex].url;
        modalImage.style.display = 'block';
        modalVideo.style.display = 'none';
      }
    }
  </script>

</body>
</html>

