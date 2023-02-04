# web-programming 1 UAS
 html-css
 menu halaman informasi
![image](https://user-images.githubusercontent.com/92699467/216757251-5837c451-7d00-4092-946e-325c71a63052.png)

sc halaman informasi
![image](https://user-images.githubusercontent.com/92699467/216757312-c0f8a4a4-a108-454f-b3e2-c01f45df0d2d.png)

halaman login
![image](https://user-images.githubusercontent.com/92699467/216757323-08c03057-f481-4a1b-b74b-fee663c76e8b.png)

sourcecode
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE-edge">
    <meta name="Viewport" content="width=device-width, initial-scale=1.8">
    <script src="https://kit.fontawesome.com/64d58efce2.js" crossorigin="anonymous"></script>

    <!-- ===== Iconscout CSS ===== -->
  <link rel="stylesheet" href="style.css" />


    <title> LOGIN</title>
</head>

<body>

    <!-- navbar -->
    <header class="header">
        <h1 class="logo"><a href="/LOGIN/">LailWebStore</a></h1>
        <ul class="main-nav">
            <li><a href="/HOME/index.html">Home</a></li>
            <li><a href="/LOGIN/">Login</a></li>
            <li><a href="/product/">product</a></li>
            <li><a href="/about/about.html">about</a></li>
        </ul>
    </header>

    <!-- end of navbar -->

    <div class="container">
        <div class="forms-container">
          <div class="signin-signup">
            <form action="#" class="sign-in-form">
              <h2 class="title">Sign in</h2>
              <div class="input-field">
                <i class="fas fa-user"></i>
                <input type="email" placeholder="Email" id="email_signin" />
              </div>
              <div class="input-field">
                <i class="fas fa-lock"></i>
                <input type="password" placeholder="Password" id="psw_signin" autocomplete="new-password" />
              </div>
              <input type="submit" value="Login" href="/product/" id="signin-button" class="btn solid" />
              <a href="/product/" class="btn">login sekarang</a>
              <p class="social-text">Or Sign in with social platforms</p>
              <div class="social-media">
                <a href="#" class="social-icon">
                  <i class="fab fa-facebook-f"></i>
                </a>
                <a href="#" class="social-icon">
                  <i class="fab fa-twitter"></i>
                </a>
                <a href="#" class="social-icon">
                  <i class="fab fa-google"></i>
                </a>
                <a href="#" class="social-icon">
                  <i class="fab fa-linkedin-in"></i>
                </a>
              </div>
            </form>
            <form action="#" class="sign-up-form">
              <h2 class="title">Sign up</h2>
              <div class="input-field">
                <i class="fas fa-user"></i>
                <input type="text" placeholder="Name" id="name" />
              </div>
              <div class="input-field">
                <i class="fas fa-phone"></i>
                <input type="text" placeholder="No HP" id="nohp" />
              </div>
              <div class="input-field">
                <i class="fas fa-envelope"></i>
                <input type="email" placeholder="Email" id="email_signup" />
              </div>
              <div class="input-field">
                <i class="fas fa-lock"></i>
                <input type="password" placeholder="Password" id="psw_signup" autocomplete="new-password" />
              </div>
              <input type="submit" class="btn" id="signup-button" value="Sign up" />
              <p class="social-text">Or Sign up with social platforms</p>
              <div class="social-media">
                <a href="#" class="social-icon">
                  <i class="fab fa-facebook-f"></i>
                </a>
                <a href="#" class="social-icon">
                  <i class="fab fa-twitter"></i>
                </a>
                <a href="#" class="social-icon">
                  <i class="fab fa-google"></i>
                </a>
                <a href="#" class="social-icon">
                  <i class="fab fa-linkedin-in"></i>
                </a>
              </div>
            </form>
          </div>
        </div>
  
        <div class="panels-container">
          <div class="panel left-panel">
            <div class="content">
              <h3>silahkan daftar ?</h3>
              <p>website ini adalah website pembelian kpop merchant!</p>
              <button class="btn transparent" id="sign-up-btn">daftar</button>
            </div>
            <img src="img/log.svg" class="image" alt="" />
          </div>
          <div class="panel right-panel">
            <div class="content">
              <h3>silahkan login ?</h3>
              <p>di LailWebStore.</p>
              <button class="btn transparent" id="sign-in-btn">Sign in</button>
            </div>
            <img src="img/register.svg" class="image" alt="" />
          </div>
        </div>
      </div>
 
      <div class="footer-content">
        <h3>Pemrogrman Website 1</h3>
        <p>UAS</p>
        <ul class="socials">
            <li><a href="https://www.facebook.com/laila.z.arifah"><i class="fa fa-facebook"></i></a></li>
            <li><a href="https://www.twitter.com/lailazanubaA"><i class="fa fa-twitter"></i></a></li>
            <li><a href="#"><i class="fa fa-instagram"></i></a></li>
            <li><a href="#"> <i class="fa fa-youtube"></i></a></li>
            <li><a href="#"><i class="fa fa-linkedin-square"></i></a></li>
        </ul>
    </div>
    <div class="footer-bottom">
        <p>copyright &copy;2023 Website1. designed by <span> -20552011290 - Laila Zanuba Arifah_TIFK20 . All Rights
                Reserved.&copy;</p>
    </div>
    </section>
      <script type="module" src="myscript.js"></script>
      <script src="app.js"></script>
    </body>
  </html>
  
  halaman register
  ![image](https://user-images.githubusercontent.com/92699467/216757370-52a26ab7-2a5a-4a1a-a765-e3ff45b7a6b2.png)

validasi menggunakan firebase
![image](https://user-images.githubusercontent.com/92699467/216757404-2d3730e5-21c5-4489-aadb-31be05a4dde9.png)

myscript.js code
// Import the functions you need from the SDKs you need
import { initializeApp } from "https://www.gstatic.com/firebasejs/9.8.2/firebase-app.js";
// import { getAuth, createUserWithEmailAndPassword } from "firebase/auth";
import { getAuth, createUserWithEmailAndPassword, signInWithEmailAndPassword, signOut } from "https://www.gstatic.com/firebasejs/9.8.2/firebase-auth.js";
import { getDatabase, set, ref, update } from "https://www.gstatic.com/firebasejs/9.8.2/firebase-database.js";
import {getFirestore, setDoc, addDoc,doc } from "https://www.gstatic.com/firebasejs/9.8.2/firebase-firestore.js";

// import { getDatabase } from "firebase/database";

// TODO: Add SDKs for Firebase products that you want to use
// https://firebase.google.com/docs/web/setup#available-libraries

        
          // Your web app's Firebase configuration
          // For Firebase JS SDK v7.20.0 and later, measurementId is optional
          const firebaseConfig = {
            apiKey: "AIzaSyAVMBO5YyXXe1pdhlSFTGclrLJOS4bIyT4",
            authDomain: "login-b4b35.firebaseapp.com",
            projectId: "login-b4b35",
            storageBucket: "login-b4b35.appspot.com",
            messagingSenderId: "1028878181049",
            appId: "1:1028878181049:web:e9e9754d3af6f1bd12b168",
            measurementId: "G-60S889VH8G"
          };
         
          // Initialize Firebase
          const app = initializeApp(firebaseConfig);
const auth = getAuth(app);
const database = getDatabase(app);
const db = getFirestore(app);
let signinButton = document.getElementById("signin-button");
let signupButton = document.getElementById("signup-button");


submitData.addEventListener('click', (e)=>{})
addDoc(doc(db, "kpop",{
  name: "Jakarta",
state:"ID",
country:"IDN"}));
signupButton.addEventListener("click", (e) => {
  let name = document.getElementById("name").value;
  let nohp = document.getElementById("nohp").value;
  let emailSignup = document.getElementById("email_signup").value;
  let passwordSignup = document.getElementById("psw_signup").value;

  createUserWithEmailAndPassword(auth, emailSignup, passwordSignup)
    .then((userCredential) => {
      // Signed in
      const user = userCredential.user;

      set(ref(database, "users/" + user.uid), {
        name: name,
        nohp: nohp,
        email: emailSignup,
        password: passwordSignup
      })
        .then(() => {
          // Data saved successfully!
          alert("user telah sukses dibuat");
        })
        .catch((error) => {
          //the write failed
          alert(error);
        });
    })
    .catch((error) => {
      const errorCode = error.code;
      const errorMessage = error.message;
      alert(errorMessage);
    });
});

signinButton.addEventListener("click", (e) => {
  let emailSignin = document.getElementById("email_signin").value;
  let passwordSignin = document.getElementById("psw_signin").value;
  signInWithEmailAndPassword(auth, emailSignin, passwordSignin)
    .then((userCredential) => {
      // Signed in
      const user = userCredential.user;
      let lgDate = new Date();
      update(ref(database, "users/" + user.uid), {
        last_login: lgDate
      })
        .then(() => {
          // Data saved successfully!
          //   alert("user telah sukses login");
          location.href = "http://127.0.0.1:5500/PROJECT WEB1 UTS/LOGIN/admin.html";
        })
        .catch((error) => {
          //the write failed
          alert(error);
        });
    })
    .catch((error) => {
      const errorCode = error.code;
      const errorMessage = error.message;
      alert(errorMessage);
    });
  signOut(auth)
    .then(() => {})
    .catch((error) => {});
});


app.js
const sign_in_btn = document.querySelector("#sign-in-btn");
const sign_up_btn = document.querySelector("#sign-up-btn");
const container = document.querySelector(".container");

sign_up_btn.addEventListener("click", () => {
  container.classList.add("sign-up-mode");
});

sign_in_btn.addEventListener("click", () => {
  container.classList.remove("sign-up-mode");
});


halaman produk
![image](https://user-images.githubusercontent.com/92699467/216757443-df9572d8-5dbf-4b03-85e9-01d72083c86e.png)

![image](https://user-images.githubusercontent.com/92699467/216757471-714cbcba-93eb-46eb-9ae1-a4e74999d1f3.png)

![image](https://user-images.githubusercontent.com/92699467/216757487-505d1e4e-4497-4dc4-a4ea-9852f03b2244.png)

sorce code
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE-edge">
    <meta name="Viewport" content="width=device-width, initial-scale=1.8">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.2/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-Zenh87qX5JnK2Jl0vWa8Ck2rdkQ2Bzep5IDxbcnCeuOxjzrPF/et3URy9Bv1WTRi" crossorigin="anonymous">
    <link rel="stylesheet" href="./style.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">

    <link rel="stylesheet"
    href="https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css">
    <title> product</title>
</head>

<body>
    <!-- navbar -->
    <header class="header">
        <h1 class="logo"><a href="/LOGIN/index.html">LailWeb</a></h1>
        <ul class="main-nav">
            <li><a href="/HOME/index.html">Home</a></li>
            <li><a href="/LOGIN/">Login</a></li>
            <li><a href="/product/index.html">product</a></li>
            <li><a href="/about/">about</a></li>
        </ul>

        <div class="icons">
            <div class="fas fa-search" id="search-btn"></div>
            <div class="fas fa-shopping-cart" id="cart-btn"></div>
            <div class="fas fa-bars" id="menu-btn"></div>
        </div>
    
        <div class="search-form">
            <input type="search" id="search-box" placeholder="search here...">
            <label for="search-box" class="fas fa-search"></label>
        </div>
    
        <div class="cart-items-container">
            <div class="cart-item">
                <span class="fas fa-times"></span>
                <img src="\images/chimmy.jpg" alt="">
                <div class="content">
                    <h3>cart item 01</h3>
                    <div class="price">Php 5,999/-</div>
                </div>
            </div>
            <div class="cart-item">
                <span class="fas fa-times"></span>
                <img src="\images/koya.jpg" alt="">
                <div class="content">
                    <h3>cart item 02</h3>
                    <div class="price">Php 4,500/-</div>
                </div>
            </div>
            <div class="cart-item">
                <span class="fas fa-times"></span>
                <img src="\images/shooky.jpg" alt="">
                <div class="content">
                    <h3>cart item 03</h3>
                    <div class="price">Php 5,500/-</div>
                </div>
            </div>
            <div class="cart-item">
                <span class="fas fa-times"></span>
                <img src="\images/mang.jpg" alt="">
                <div class="content">
                    <h3>cart item 04</h3>
                    <div class="price">Php 3,000/-</div>
                </div>
            </div>
            <a href="#" class="btn">checkout now</a>
        </div>
    
    </header>
    
    <!-- header section ends -->
    
    <!-- about us section starts  -->
    
    <section class="about" id="about">
    
        <h1 class="heading"> <span>Magic Shop</span> Surprises!</h1>
    
        <div class="row">
    
            <div class="image">
                <img src="\images/ms logo.gif" alt="">
            </div>
    
            <div class="content">
                <h3>AYO BELI MERCHAN KPOP DI LailWebStore ?</h3>
                <p>kami menyediakan merchant kpop dengan High quality products dan harga murah!  </p>
                <a href="#menu" class="btn">belanja sekarang!</a>
            </div>
    
        </div>
    
    </section>
    
    <!-- about us section ends -->
    
    <!-- bt21  section starts  -->
    
    <section class="menu" id="menu">
    
        <h1 class="heading"> BT21 <span>comboBTS!</span> </h1>
    
        <div class="box-container">
    
            <div class="box">
                <img src="\images/chimmy.jpg" alt="">
                <h3>BT21 CHIMMY</h3>
                <div class="price">RP. 300.000 <span>500.000</span></div>
                <a href="#" class="btn">tambahkan</a>
            </div>
    
            <div class="box">
                <img src="\images/koya.jpg" alt="">
                <h3>BT21 KOYA</h3>
                <div class="price">RP. 250.000<span>450.000</span></div>
                <a href="#" class="btn">tambahkan</a>
            </div>
    
            <div class="box">
                <img src="\images/shooky.jpg" alt="">
                <h3>BT21 SHOOKY</h3>
                <div class="price">RP 500.000 <span>600.000</span></div>
                <a href="#" class="btn">tambahkan</a>
            </div>
    
            <div class="box">
                <img src="\images/mang.jpg" alt="">
                <h3>BT21 MANG</h3>
                <div class="price">Rp 300.000 <span>399.900</span></div>
                <a href="#" class="btn">tambahkan</a>
            </div>
    
            <div class="box">
                <img src="\images/tata.jpg" alt="">
                <h3>BT21 TATA</h3>
                <div class="price">RP 600.000 <span>649.900</span></div>
                <a href="#" class="btn">tambahkan</a>
            </div>
    
            <div class="box">
                <img src="\images/rj.jpg" alt="">
                <h3>BT21 RJ</h3>
                <div class="price">RP 620.000 <span>680.000</span></div>
                <a href="#" class="btn">tambahkan</a>
    
                
            </div>
    
        </div>
    
    </section>
    
    
    
    
    <!-- bt21 section ends -->
    
    <section class="products" id="products">
    
        <h1 class="heading"> album<span> terbaru </span> </h1>
    
        <div class="box-container">
    
            <div class="box">
                <div class="icons">
                    <a href="#" class="fas fa-shopping-cart"></a>
                    <a href="#" class="fas fa-heart"></a>
                    <a href="#" class="fas fa-eye"></a>
                </div>
                <div class="image">
                    <img src="\images/dimension answer.jpg" alt="">
                    <img aria-setsize="20px";
                </div>
                <div class="content">
                    <h3>Enhypen Dimension:Answer</h3>
                    <div class="stars">
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star-half-alt"></i>
                    </div>
                    <div class="price">Rp 180.000<span>Rp 200.000</span></div>
                </div>
            </div>
    
            <div class="box">
                <div class="icons">
                    <a href="#" class="fas fa-shopping-cart"></a>
                    <a href="#" class="fas fa-heart"></a>
                    <a href="#" class="fas fa-eye"></a>
                </div>
                <div class="image">
                    <img src="\images/formula of love.jpg" alt="">
                </div>
                <div class="content">
                    <h3>Twice Formula of love</h3>
                    <div class="stars">
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star-half-alt"></i>
                    </div>
                    <div class="price">Rp 250.000<span>RP 300.000</span></div>
                </div>
            </div>
    
            <div class="box">
                <div class="icons">
                    <a href="#" class="fas fa-shopping-cart"></a>
                    <a href="#" class="fas fa-heart"></a>
                    <a href="#" class="fas fa-eye"></a>
                </div>
                <div class="image">
                    <img src="\images/butter.jpg" alt="">
                </div>
                <div class="content">
                    <h3>BTS Butter</h3>
                    <div class="stars">
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star-half-alt"></i>
                    </div>
                    <div class="price">Rp.500.000 <span>Rp 800.000</span></div>
                </div>
            </div>
    
        </div>
    
    </section>
    
    <!-- review ng mga asawa ko section starts  -->
    
    <section class="review" id="review">
    
        <h1 class="heading"> ulasan <span> pelanggan</span> </h1>
    
        <div class="box-container">
    
            <div class="box">
                <img src="\images/quote-img.png" alt="" class="quote">
                <p>it's very kiyowo and i really love this shop, the services are very kind to help me!!</p>
                <img src="\images/asawa ko.jpg" class="user" alt="">
                <h3>Christopher bang</h3>
                <div class="stars">
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star-half-alt"></i>
                </div>
            </div>
    
            <div class="box">
                <img src="\images/quote-img.png" alt="" class="quote">
                <p>Konnichiwa! This shop is Kawaii!I didn't expect the high quality that i received. <img src="\images/nabaccla ako sayo.jpg" class="user" alt="">
                <h3>Sana Minatozaki</h3>
                <div class="stars">
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star-half-alt"></i>
                </div>
            </div>
            
            <div class="box">
                <img src="\images/quote-img.png" alt="" class="quote">
                <p>Ogu baby gwenchana? Yay! Super happy that i found this shop!</p>
                <img src="\images/kabit ko.jpg" class="user" alt="">
                <h3>Tae Tae</h3>
                <div class="stars">
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star-half-alt"></i>
                </div>
            </div>
    
        </div>
    
    </section>
    
    <!-- review ng mga asawa ko section ends -->
    
    <!-- contact section starts  -->
    
    <section class="contact" id="contact">
    
        <h1 class="heading"> <span>contact</span> us </h1>
    
        <div class="row">
       <iframe class="map" src="https://www.google.co.id/maps/place/Jl.+Sindangreret,+Sukasari,+Kec.+Pameungpeuk,+Kabupaten+Bandung,+Jawa+Barat/@-7.0182972,107.5894623,17z/data=!3m1!4b1!4m5!3m4!1s0x2e68ebe5d37114c1:0xa621dd48ee69668b!8m2!3d-7.0183025!4d107.591651!5m1!1e1" allowfullscreen="" loading="lazy"></iframe>
            <form action="">
                <h3>ada masalah?</h3>
                <h4>silahkan tulis problem anda di form bawah.</h4>
                <div class="inputBox">
                    <span class="fas fa-user"></span>
                    <input type="text" placeholder="name">
                </div>
                <div class="inputBox">
                    <span class="fas fa-envelope"></span>
                    <input type="email" placeholder="email">
                </div>
                <div class="inputBox">
                    <span class="fas fa-phone"></span>
                    <input type="number" placeholder="number">
                </div>
                <input type="submit" value="contact now" class="btn">
            </form>
    
        </div>
    
    </section>
    
    <!-- contact section ends -->
    
    <!-- upcoming merch section starts  -->
    
    <section class="upcoming" id="upcoming">
    
        <h1 class="heading"> YANG <span>AKAN DATANG</span> </h1>
    
        <div class="box-container">
    
            <div class="box">
                <div class="image">
                    <img src="\images/bts light stick.jpg" alt="">
                </div>
                <div class="content">
                    <a href="#" class="title">BTS Official Light Stick</a>
                    <span>AKAN TERSDIA / 25 MEI, 2023</span>
                    <p>BTS Lightstick Bomb Light Stick Bangtan Boys Concert Lamp Bluetooth Ver.3 Support for Army (BTS Ver.3).</p>
                    <a href="#" class="btn">INGATKAN SAYA</a>
                </div>
            </div>
    
            <div class="box">
                <div class="image">
                    <img src="\images/blackpink light stick.jpg" alt="">
                </div>
                <div class="content">
                    <a href="#" class="title">blackpink official Light Stick</a>
                    <span>AKAN TERSEDIA / 29 MEI, 2023</span>
                    <p>Hammer Light stick Hammer Bong Concert Glow Lamp【Fast Delivery/COD】.</p>
                    <a href="#" class="btn">INGATKAN SAYA</a>
                </div>
            </div>
    
            <div class="box">
                <div class="image">
                    <img src="\images/twice light stick.jpg" alt="">
                </div>
                <div class="content">
                    <a href="#" class="title">Twice Official Light Stick</a>
                    <span>AKAN TERSEDIA / 5 JUNI, 2023</span>
                    <p>CANDYBONG Z Light Stick With Bluetooth or without Bluetooth. TWICE CANDY BONG Z LightStick Version-2.</p>
                    <a href="#" class="btn">INGATKAN SAYA</a>
                </div>
            </div>
    
        </div>
    
    </section>
    
    <!-- upcoming merch section ends -->
    
    <!-- footer section starts  -->
    
    <div class="footer-content">
        <h3>Pemrogrman Website 1</h3>
        <p>UAS</p>
        <ul class="socials">
            <li><a href="https://www.facebook.com/laila.z.arifah"><i class="fa fa-facebook"></i></a></li>
            <li><a href="https://www.twitter.com/lailazanubaA"><i class="fa fa-twitter"></i></a></li>
            <li><a href="#"><i class="fa fa-instagram"></i></a></li>
            <li><a href="#"> <i class="fa fa-youtube"></i></a></li>
            <li><a href="#"><i class="fa fa-linkedin-square"></i></a></li>
        </ul>
    </div>
    <div class="footer-bottom">
        <p>copyright &copy;2023 Website1. designed by <span> -20552011290 - Laila Zanuba Arifah_TIFK20 . All Rights
                Reserved.&copy;</p>
    </div>
    </section>
    
    <!-- footer section ends -->
    
    

    <!-- custom js file link  -->
    <script src="script.js"></script>
    
    </body>
    </html>
    
    halaman contact us
    ![image](https://user-images.githubusercontent.com/92699467/216758779-c1c4ad0c-4ef8-44ee-97fb-0a15d1a33da0.png)
 
 sourcecode contact us
<!DOCTYPE html>
<html>

<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title>LailaWeb</title>
	<link rel="stylesheet" type="text/css" href="css/style.css">
	<link rel="stylesheet" href="./style.css">

</head>

<body>

	<!-- navbar -->
	<header class="header">
		<h1 class="logo"><a href="/LOGIN/index.html">LailWeb</a></h1>
		<ul class="main-nav">
			<li><a href="/HOME/index.html">Home</a></li>
			<li><a href="/LOGIN/">Login</a></li>
			<li><a href="/product/index.html">product</a></li>
			<li><a href="/contact/contact.html">contact</a></li>
		</ul>
	</header>
	<div class="icons">
        <div class="fas fa-search" id="search-btn"></div>
        <div class="fas fa-shopping-cart" id="cart-btn"></div>
        <div class="fas fa-bars" id="menu-btn"></div>
    </div>

    <div class="search-form">
        <input type="search" id="search-box" placeholder="search here...">
        <label for="search-box" class="fas fa-search"></label>
    </div>


</header>

<!-- header section ends -->

<!-- home section starts  -->

<section class="home" id="home">

    <div class="content">
        <h3>AYO BELI sekarang</h3>
        <p>Dapatkan album dan merchandise biasmu sekarang!</p>
        <a href="#" class="btn">gas!</a>
    </div>

<section class="contact" id="contact">

    <h1 class="heading"> <span>contact</span> us </h1>

    <div class="row">
   <iframe class="map" src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d15359.694598142603!2d119.90718867832489!3d15.755177775208551!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x339409c6015c51e3%3A0x2059f5e2a7bd9b6a!2sLipay%2C%20Santa%20Cruz%2C%20Zambales!5e0!3m2!1sen!2sph!4v1651902796593!5m2!1sen!2sph" allowfullscreen="" loading="lazy"></iframe>
        <form action="">
            <h3>ada masalah?</h3>
            <h4>silahkan isi form di bawah ini.</h4>
            <div class="inputBox">
                <span class="fas fa-user"></span>
                <input type="text" placeholder="name">
            </div>
            <div class="inputBox">
                <span class="fas fa-envelope"></span>
                <input type="email" placeholder="email">
            </div>
            <div class="inputBox">
                <span class="fas fa-phone"></span>
                <input type="number" placeholder="number">
            </div>
            <input type="submit" value="contact now" class="btn">
        </form>

    </div>

</section>

<!-- contact section ends -->

<!-- footer section starts  -->

<section class="footer">

    <div class="share">
        <a href="#" class="fab fa-facebook-f"></a>
        <a href="#" class="fab fa-twitter"></a>
        <a href="#" class="fab fa-instagram"></a>
        <a href="#" class="fab fa-linkedin"></a>
        <a href="#" class="fab fa-pinterest"></a>
        
    </div>

    <div class="links">
        <a href="index.html">home</a>
        <a href="contact us.html">contact us</a>
        <a href="#contact">Contact us</a>
        
    </div>

    <div class="credit"><span><a href="https://www.weverseshop.io/">LailWebStore </span> | @COPYRIGHT BY - 20552011290 -LAILA ZANUBA Arifah_TIFK20_UAS . ALL RIGHT RESERVED.&copy;</div>

</section>

<!-- footer section ends -->


<!-- custom js file link  -->
<script src="script.js"></script>

	<script type="text/javascript">
		$(document).ready(function () {
			$(".bg-loader").hide();
		})
	</script>
</body>

</html>



