# Fitness-Webste
website for gym
<!DOCTYPE html>
<html lang="en">
<head>
  
  <!--  Meta  -->
  <meta charset="UTF-8" />
  <title>FITNESS WEBSITE</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  
  <!--  Styles  -->
  <link rel="stylesheet" href="styles/index.processed.css">
  <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css">
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@900&display=swap" rel="stylesheet">
</head>
<body>
  <!--navbar-->
  <div class="navbar">
    <input type="checkbox" class="checkbox" id="click" hidden>
    <!--sidebar-->
    <div class="sidebar">
      <label for="click">      <!--to wrap the click event-->
      <div class="menu-icon">
        <div class="line line-1"></div>
        <div class="line line-2"></div>
        <div class="line line-3"></div>
      </div>
      </label>
        <ul class="social-media-icon">
           <li>
             <a href="#" class="social-link"><i class="fa fa-facebook-official" aria-hidden="true"></i>
             </a>
           </li>
           <li>
             <a href="#" class="social-link"><i class="fa fa-twitter" aria-hidden="true"></i>
             </a>
           </li>
           <li>
             <a href="#" class="social-link"><i class="fa fa-google" aria-hidden="true"></i>
             </a>
           </li>
      </ul>
      <div class="year">
        <p>2022</p>
      </div>
    </div>
    <!--end of sidebar-->
    
    <!--navigation-->
    <div class="navigation">
      <div class="navigation-header">
        <h1 class="navigation-heading">Bodyline Gym</h1>
        <form class="navigation-search">
          <input type="text" class="search-input" placeholder:"search...">
          <button class="search-button"><i class="fa fa-search" aria-hidden="true"></i></button>
        </form>
      </div>
      
      <ul class="navigation-list">
        <li class="navigation-item"><a href="#" class="nav-link">Home</a></li>
        <li class="navigation-item"><a href="#" class="nav-link">About Us</a></li>
        <li class="navigation-item"><a href="#" class="nav-link">Facilities</a></li>
        <li class="navigation-item"><a href="#" class="nav-link">Contact Us</a></li>
      </ul>
      
      <div class="copyright">
        <p>&copy, 2022 Body Line Gym. All right reserved</p>
      </div>
    </div>
    <!--end of navigation-->
  </div>
  <!--end of navbar-->
  <!--header-->
  <header class="header">
    <div class="hbrand">
      <h3 class="gym-heading">Bodyline Gym</h3>
    </div>
    <div class="banner">
      <h1 class="banner-heading">Welcome to BodyLine Gym</h1>
      <p class="banner-paragraph">Fitness destination</p>
      <button class="banner-button">Enter</button>
    </div>
  </header>
  <!--end of header-->
  <!--About Us-->
  <section class="aboutus">
    <div class="aboutus-content">
      <h1 class="aboutus-heading">About Us</h1>
      <div class="underline">
        <div class="small-underline"></div>
        <div class="big-underline"></div>
      </div>
      <h3 class="sub-heading">Bodyline Gym</h3>
      <p class="aboutus-paragraph">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Impedit libero dolores temporibus vel quasi quod non eligendi deserunt cumque reprehenderit labore commodi, sit explicabo enim totam, in repudiandae, necessitatibus odit.lorem</p>
      <button class="aboutus-button">
        Read more...
        <i class="fa fa-angle-double-right btn-arrw"></i>
        </button>
    </div>
    
    <div class="about-us-images">
      <img src="https://i.postimg.cc/T3RSdMKg/IMG-20200416-WA0015.jpg" class="img img1" alt="">
      <img src="https://i.postimg.cc/m2WJnFRd/IMG-20200416-WA0017.jpg" class="img img2"alt="">
      <img src="https://i.postimg.cc/NjBhK2zy/IMG-20200416-WA0009.jpg" class="img img3">
      <img src="https://i.postimg.cc/tgrHQRDs/IMG-20200416-WA0006.jpg" class="img img4"alt="">
    </div>
  </section>
  <!--end of About Us-->
  
  <!--Facilities-->
  <section class="facilities">
    <div class="faclities-header">
      <h1 class="facilities-heading">Facilities in Bodyline Gym</h1>
      <div class="underline">
        <div class="small-underline"></div>
        <div class="big-underline"></div>
      </div>
      </div>
    
      <div class="facilities-cards-wrapper">
        <div class="facilities-cards">
          <img src="https://i.postimg.cc/G21mtmGq/IMG-20200416-WA0002.jpg" alt="" class="faclities-img">
          <div class="card-content">
            <h4 class="card-heading">Equip1</h4>
            <p class="card-paragraph">Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
            <button class="card-btn">Check it<i class="fa fa-angle-double-right btn-arrw"></i>
            </button>
          </div>
        </div>
        
        <div class="facilities-cards">
          <img src="https://i.postimg.cc/6pg3s03s/IMG-20200416-WA0001.jpg" alt="" class="faclities-img">
          <div class="card-content">
            <h4 class="card-heading">Equip2</h4>
            <p class="card-paragraph">Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
            <button class="card-btn">Check it<i class="fa fa-angle-double-right btn-arrw"></i>
            </button>
          </div>
        </div>
        
        <div class="facilities-cards">
          <img src="https://i.postimg.cc/6pg3s03s/IMG-20200416-WA0001.jpg" alt="" class="faclities-img">
          <div class="card-content">
            <h4 class="card-heading">Equip2</h4>
            <p class="card-paragraph">Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
            <button class="card-btn">Check it<i class="fa fa-angle-double-right btn-arrw"></i>
            </button>
          </div>
        </div>
        
        <div class="facilities-cards">
          <img src="https://i.postimg.cc/XJ3n3D6P/IMG-20200416-WA0004.jpg" alt="" class="faclities-img">
          <div class="card-content">
            <h4 class="card-heading">Equip3</h4>
            <p class="card-paragraph">Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
            <button class="card-btn">Check it<i class="fa fa-angle-double-right btn-arrw"></i>
            </button>
          </div>
        </div>
      </div>
    <div class="check-all-wrpr">
      <button class="check-all-btn">Check all facilities</button>
    </div>
  </section>
  <!--end of facilities-->
  
  <!--Customers-->
  <section class="customers">
    <div class="faclities-header">
      <h1 class="facilities-heading">Our Customers</h1>
      <div class="underline">
        <div class="small-underline"></div>
        <div class="big-underline"></div>
      </div>
      </div>
    <p class="customers-paragraph">Lorem ipsum dolor sit amet consectetur adipisicing elit. Quidem aut at iste, mollitia quisquam, </p>
    
    <div class="customers-cards-wrapper">
      <div class="customer-card">
        <div class="customer-img-wrapper">
        </div>
        <div class="customer-info">
          <h3 class="customer-name">Customer1</h3>
          <p class="customer-paragraph-1">Happy Cusstomer</p>
          <p class="customer-paragraph-2">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Alias voluptatum voluptas, molestias, blanditiis fugiat ad sunt sapiente expedita odit, assumenda non eveniet sequi maxime aspernatur eum dolorum porro repellat magnam.</p>
        </div>
      </div>
      
      <div class="customer-card">
        <div class="customer-img-wrapper">
        </div>
        <div class="customer-info">
          <h3 class="customer-name">Customer2 </h3>
          <p class="customer-paragraph-1">Happy Cusstomer</p>
          <p class="customer-paragraph-2">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Alias voluptatum voluptas, molestias, blanditiis fugiat ad sunt sapiente expedita odit, assumenda non eveniet sequi maxime aspernatur eum dolorum porro repellat magnam.</p>
        </div>
      </div>
      
     <div class="customer-card">
        <div class="customer-img-wrapper">
        </div>
        <div class="customer-info">
          <h3 class="customer-name">Customer3</h3>
          <p class="customer-paragraph-1">Happy Cusstomer</p>
          <p class="customer-paragraph-2">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Alias voluptatum voluptas, molestias, blanditiis fugiat ad sunt sapiente expedita odit, assumenda non eveniet sequi maxime aspernatur eum dolorum porro repellat magnam.</p>
        </div>
      </div>
    </div>
  </section>
  <!--end of customers-->
  
  <!--footer-->
  <footer class="footer">
    <div class="main-part">
      <div class="footer-list-wrap">
        <h3 class="footer-heading">Bodyline Gym</h3>
        <ul class="footer-list">
          <li class="footer-list-item">
            <a href="#" class="footer-list-link">support@bodylinegym.com</a>
          </li>
          
          <li class="footer-list-item">
            <a href="#" class="footer-list-link">support@bodylinegym.com</a>
          </li>
          
          <li class="footer-list-item">
            <a href="#" class="footer-list-link">+91 123 234 2345</a>
          </li>
        </ul>
      </div>
      
      <div class="footer-list-wrap">
        <h3 class="footer-heading">Explore</h3>
        <ul class="footer-list">
          <li class="footer-list-item">
            <a href="#" class="footer-list-link">Home</a>
          </li>
          
          <li class="footer-list-item">
            <a href="#" class="footer-list-link">Facilities</a>
          </li>
          
          <li class="footer-list-item">
            <a href="#" class="footer-list-link">Gallery</a>
          </li>
          
          <li class="footer-list-item">
            <a href="#" class="footer-list-link">Charges</a>
          </li>
          
          <li class="footer-list-item">
            <a href="#" class="footer-list-link">Location</a>
          </li>
          
          <li class="footer-list-item">
            <a href="#" class="footer-list-link">Policies</a>
          </li>
                  
        </ul>
      </div>
      
      <div class="contact">
        <h3 class="footer-heading">Contact Us</h3>
        <p>Sign up for updates</p>
        <form action="" class="footer-form">
          <input type="text" class="footer-input" placeholder="Your email...">
          <button class="footer-btn">Sign up</button>
        </form>
      </div>
      
      <div class="gallery">
        <h3 class="footer-heading-gallery">Gallery</h3>
        <div class="gallery-images">
          <div class="image-wrapper">
            <img src="https://i.postimg.cc/Xq8S2vg8/IMG-20200316-WA0000.jpg" alt="" class="footer-image">
          </div>
          
          <div class="image-wrapper">
            <img src="https://i.postimg.cc/tgyJJsMq/IMG-20200416-WA0019.jpg" alt=""  class="footer-image">
          </div>
          
          <div class="image-wrapper">
            <img src="https://i.postimg.cc/5tRt3st0/IMG-20200416-WA0012.jpg" alt="" class="footer-image">
          </div>
          
          <div class="image-wrapper">
            <img src="https://i.postimg.cc/Ssw3kn9x/IMG-20200416-WA0010.jpg" alt=""  class="footer-image">
          </div>
          
          <div class="image-wrapper">
            <img src="https://i.postimg.cc/2yrmBnn3/hhh.jpg" alt=""  class="footer-image">
          </div>
          
          <div class="image-wrapper">
            <img src="https://i.postimg.cc/htHrrsvy/bar.jpg" alt="" class="footer-image">
          </div>
        
        </div>
      </div>
    </div>
    
    <div class="maker">
      <div class="copyright-text">
        <p>Copyright &copy; 2022 .Bodyline Gym.All Right Reserved</p>
      </div>
      
     <!-- <div class="right-end">
        <p>Created with <i class="fa fa-heart"></i>by<span> Ved Prakash Singh</span</p>
      </div>
      -->

    </div>
  </footer>
  
  <!--end of footer-->
  
  <script src="scripts/index.js"></script>
</body>
</html>
