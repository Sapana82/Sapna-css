Html:-
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>GroceryHub.</title>
  <link rel="stylesheet" href="Grocery.css">
  <link href='https://unpkg.com/boxicons@2.1.4/css/boxicons.min.css' rel='stylesheet'>
</head>

<body>

  <!-- Navbar -->
  <div class="navbar">
    <!-- Left: Image Logo -->
    <h2 class="logo" style="color: black;">GroceryHub.</h2>

    <!-- Middle: Search Bar -->
    <div class="searchbar">
      <input type="text" placeholder="Search Items...">
      <div class="magnify">
        <i class='bx bx-search-alt-2'></i>
      </div>
    </div>

    <!-- Right: Menu and User/Login -->
    <div class="nav-items">
      <a href="#">Home</a>
      <a href="#">Services</a>
      <a href="#">About</a>
      <a href="#">Contact</a>
    </div>

    <div class="user-login">
      <div class="userlogo">
        <i class='bx bxs-user'></i>
      </div>
      <a href="#">Login</a>
    </div>
  </div>

  <!-- Image Carousel -->
  <section class="container1">
    <div class="image_item">
      <div class="img1">
        <img src="https://atlas-content-cdn.pixelsquid.com/theme%2F1937350336096245322%2F%248t7wtb0dauk-Header_IMG.jpg"
          alt="first grocery ">

      </div>
      <div class="img1">
        <img src="https://as2.ftcdn.net/v2/jpg/05/04/78/17/1000_F_504781729_FPGJKd9SfREE3lPo1DJCKBpEnsuhfjOQ.jpg"
          alt="Avenger">
        <p class="p1">Lorem, ipsum.</p>
        <p class="p1 p2">Lorem ipsum dolor sit amet consectetur adipisicing elit. Ut quisquam placeat officia.</p>
      </div>
      <div class="img1">
        <img src="https://t3.ftcdn.net/jpg/06/30/03/48/360_F_630034819_XG8RyZJRK5Q06OTEjDXStBPaZjRGn0kF.jpg" alt="Hulk">
        <p class="p1">Lorem, ipsum.</p>
        <p class="p1 p2">Lorem ipsum dolor sit amet consectetur adipisicing elit. Ut quisquam placeat officia.</p>
      </div>
    </div>
  </section><section class="container2">

    <div class="commoncontain">
      <h2 class="box_heading">My Smart Basket</h2>
      <div class="commoncontainer">
        <div class="grocery-items">
          <div class="box_item">
            <div class="box_image">
              <img src="https://www.bigbasket.com/media/uploads/p/m/10000067_26-fresho-capsicum-green.jpg?tr=w-154,q-80"
                alt="Capsicum">
            </div>
            <h2>Capsicum - Green (Loose)</h2>
            <span>₹80</span>
            <div class="box_button">
              <button class="ibutton"><i class='bx bxs-bookmark' style='color:#000000' ></i></i></button>
              <button class="add"><span>Add</span></button>
            </div>
          </div>
        </div>


        <div class="grocery-items">
          <div class="box_item">
            <div class="box_image">
              <img src="https://www.bigbasket.com/media/uploads/p/m/10000070_16-fresho-carrot-orange.jpg?tr=w-154,q-80"
                alt="carrot">
            </div>
            <h2>Carrot - Orange (Loose)</h2>
            <span>₹50.5</span><span></span>
            <div class="box_button">
              <button class="ibutton"><i class='bx bxs-bookmark' style='color:#000000' ></i></i></button>
              <button class="add"><span>Add</span></button>
            </div>
          </div>
        </div>
        
        <div class="grocery-items">
          <div class="box_item">
            <div class="box_image">
              <img src="https://www.bigbasket.com/media/uploads/p/m/10000074_20-fresho-cauliflower.jpg?tr=w-154,q-80"
                alt="cauliflower">
            </div>
            <h2>Cauliflower</h2>
            <span>₹32.5</span>
            <div class="box_button">
              <button class="ibutton"><i class='bx bxs-bookmark' style='color:#000000' ></i></i></button>
              <button class="add"><span>Add</span></button>
            </div>
          </div>
        </div>

        <div class="grocery-items">
          <div class="box_item">
            <div class="box_image">
              <img
                src="https://www.bigbasket.com/media/uploads/p/m/10000326_16-fresho-coriander-leaves.jpg?tr=w-154,q-80"
                alt="coriander">
            </div>
            <h2>Coriander Leaves</h2>
            <span>₹111.78</span>
            <div class="box_button">
              <button class="ibutton"><i class='bx bxs-bookmark' style='color:#000000' ></i></button>
              <button class="add"><span>Add</span></button>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <section class="container3">
    <div class="more_details">
      <div class="offers">
        <h2>OFFERS</h2>
        <div class="commonimgs">
          <img class="commonimg" src="https://www.bigbasket.com/media/customPage/b01eee88-e6bc-410e-993c-dedd012cf04b/91e53046-98e0-4c5b-ae53-7d073e5210e1/2b94a9cf-895f-460d-849a-1eee860c974c/hp_dow-topoffersStorefront_m_480_250723_01.jpg?tr=w-480,q-80" alt="offer1">
          <img class="commonimg" src="https://www.bigbasket.com/media/customPage/b01eee88-e6bc-410e-993c-dedd012cf04b/91e53046-98e0-4c5b-ae53-7d073e5210e1/2b94a9cf-895f-460d-849a-1eee860c974c/hp_dow-topoffersStorefront_m_480_250723_01.jpg?tr=w-480,q-80" alt="offer2">
          <img class="commonimg" src="https://www.bigbasket.com/media/customPage/b01eee88-e6bc-410e-993c-dedd012cf04b/91e53046-98e0-4c5b-ae53-7d073e5210e1/2b94a9cf-895f-460d-849a-1eee860c974c/hp_dow-topoffersStorefront_m_480_250723_01.jpg?tr=w-480,q-80" alt="offer3">
          <img class="commonimg" src="https://www.bigbasket.com/media/customPage/b01eee88-e6bc-410e-993c-dedd012cf04b/91e53046-98e0-4c5b-ae53-7d073e5210e1/2b94a9cf-895f-460d-849a-1eee860c974c/hp_30-corner-topoffersStorefront_m_480_250723_04.jpg?tr=w-480,q-80" alt="offer4">  
        </div>
      </div>
      <div class="vegetables">
        <h2>Fruits and Vegetables</h2>
        <div class="commonimgs">
        <img class="commonimg" src="https://www.bigbasket.com/media/customPage/b01eee88-e6bc-410e-993c-dedd012cf04b/91e53046-98e0-4c5b-ae53-7d073e5210e1/41a0810e-1fc3-46e4-9d2c-7d9e79e0aa29/hp_f&v_m_fresh-vegetables_480_250923.jpg?tr=w-480,q-80" alt="veg1">
        <img class="commonimg" src="https://www.bigbasket.com/media/customPage/b01eee88-e6bc-410e-993c-dedd012cf04b/91e53046-98e0-4c5b-ae53-7d073e5210e1/41a0810e-1fc3-46e4-9d2c-7d9e79e0aa29/hp_f&v_m_cuts-&-exotics_480_250923.jpg?tr=w-480,q-80" alt="veg2">
        <img class="commonimg" src="https://www.bigbasket.com/media/customPage/b01eee88-e6bc-410e-993c-dedd012cf04b/91e53046-98e0-4c5b-ae53-7d073e5210e1/41a0810e-1fc3-46e4-9d2c-7d9e79e0aa29/hp_f&v_m_fresh-fruits_480_250923.jpg?tr=w-480,q-80" alt="veg3">
        <img class="commonimg" src="https://www.bigbasket.com/media/customPage/b01eee88-e6bc-410e-993c-dedd012cf04b/91e53046-98e0-4c5b-ae53-7d073e5210e1/41a0810e-1fc3-46e4-9d2c-7d9e79e0aa29/hp_f&v_m_herbs-&-seasoning_480_250923.jpg?tr=w-480,q-80" alt="veg4">
      </div>
      </div>
      <div class="snacks">
        <h2>Snacks Store</h2>
        <div class="commonimgs">
        <img class="commonimg" src="https://www.bigbasket.com/media/customPage/b01eee88-e6bc-410e-993c-dedd012cf04b/91e53046-98e0-4c5b-ae53-7d073e5210e1/09ece9f7-7ac9-4d1e-afbb-f8ac572add38/hp_sbf_m_biscuits-&-namkeens_480_250923.jpg?tr=w-480,q-80" alt="snack1">
        <img class="commonimg" src="https://www.bigbasket.com/media/customPage/b01eee88-e6bc-410e-993c-dedd012cf04b/91e53046-98e0-4c5b-ae53-7d073e5210e1/09ece9f7-7ac9-4d1e-afbb-f8ac572add38/hp_sbf_m_breakfast-cereals_480_250923.jpg?tr=w-480,q-80" alt="snack2">
        <img class="commonimg" src="https://www.bigbasket.com/media/customPage/b01eee88-e6bc-410e-993c-dedd012cf04b/91e53046-98e0-4c5b-ae53-7d073e5210e1/09ece9f7-7ac9-4d1e-afbb-f8ac572add38/hp_sbf_m_pasta-sauces-&-more_480_270723.jpg?tr=w-480,q-80" alt="snack3">
        <img class="commonimg" src="https://www.bigbasket.com/media/customPage/b01eee88-e6bc-410e-993c-dedd012cf04b/91e53046-98e0-4c5b-ae53-7d073e5210e1/09ece9f7-7ac9-4d1e-afbb-f8ac572add38/hp_sbf_m_sweet-cravings_480_250923.jpg?tr=w-480,q-80" alt="snack4">
      </div>
      </div>
    </div>
  </section>

  <section class="container4">
    <div class="about">
      <h2>GroceryHub -- online grocery store</h2>
      <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Necessitatibus quisquam iste, natus quos sunt asperiores autem odio minus harum aliquid iusto voluptates soluta quaerat?</p>
      <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Ipsum voluptas consequuntur quisquam sint quidem sequi, harum ullam aspernatur numquam mollitia perspiciatis obcaecati voluptatem.</p>
      <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Necessitatibus quisquam iste, natus quos sunt asperiores autem odio minus harum aliquid iusto voluptates soluta quaerat?</p>
      <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Ipsum voluptas consequuntur quisquam sint quidem sequi, harum ullam aspernatur numquam mollitia perspiciatis obcaecati voluptatem.</p>    
    </div>
  </section>

</body>

</html>
