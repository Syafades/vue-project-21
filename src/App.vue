<script setup>
import DataBarang1 from "./assets/dataBarang1";
import DataBarang2 from "./assets/dataBarang2";
import DataBarang3 from "./assets/dataBarang3";
import Datareview from "./assets/datareview";
</script>
<script>
export default {
  data: function () {
    return {
      titleHero: "Centered Hero",
      titleImage1:
        "https://s3-alpha-sig.figma.com/img/938d/648b/01303df8946b34770333262fbf4451f2?Expires=1662336000&Signature=JYq7YNOWqP9oNdFCylQ3pyt3TbrfUsZ1buRRolE9Tz2lZB-9kNZ0z~pc1vVzVN10A~xfWMvY5peJUHhFnQUvgUxzmdOnGHgx53cCordIoPtOxJ~oz5Ri5jL6iYyVZwVTpQ9-4EWV8mb3jRlvpzOsTnd1jwhz6YYy2sjOEQjv7CbSxFauSoXHvw6wREW1B-Sd34r1Vmw3XlPblApTfIrIv7QKp5H511TA71EFD~CIVY75HycyNnqZGhJseTTon377iPuvACKWFR~-2nKtY3tHMkt4RVb8WH7kI7OovJ0z0Zm9yneMb1eLzfDQvlWU41PG4EeL2-pROg4WHRIEp4etrw__&Key-Pair-Id=APKAINTVSUGEWH5XD5UA",
      titleImage2:
        "https://s3-alpha-sig.figma.com/img/d95e/4dda/de9f383fd7f21d16dcb1d32703ee8f6c?Expires=1662336000&Signature=EA-3VP5KEeMaUXpemIfKpsFkscLMikKC-srbk3JJBHx831xc1nlIduzeGewT6BTJsO3wjfQ7~Is5yYPaiqskYWnP7ei6Axdi~BvbWQLhG9efKHXI-MQFkPGTfjxN8ab-y~PJSK~2-AKzRe0pHafwxmi~VHtYQHmEwaG25HUBJAZo0qArb3T1kalTwc9BSwHJ5ztpWd34QFOjHZgokPGkt6PUkLK5jcyPz4G~HqCvYD8v~JSQU9a58WgZ~25zb~k~bsdL7aLoTXZ3kt~2I9lWiQN2vhspEvHL9QhpyECVV1YrLDiTymtES1VyKu3EL0MmSyQx4NhPO-qWe0xmgR3qqw__&Key-Pair-Id=APKAINTVSUGEWH5XD5UA",
      titleImage3:
        "https://s3-alpha-sig.figma.com/img/1cb1/86f3/f4ca61863f7d6d56ff2b76cb2d036858?Expires=1662336000&Signature=PtzaWn9gMD5uYkO9c~pXezd6U~sORWR~~oknDHc1oOrwevbrWtaqezuxKew-aPnqyda164L1qcDniDYbrpHMq270kJYrNnoz0JJ7~WREKeTWGopagfuhu9n8tJYHNQU7jztYDJVhbBvc21XaKi5n5qRZKI1HtyF47~8CNK0CnkYypYy~R7x0ky9~0FzBexSNdUNjpwkErt74etEoTgp3EF67siFw4sqk2-0epyDwKLHmhQeiIc8J0T4KbPTOpv7r7gwcmeWjUyDfhm2jkCtKsXzRCDEekAdONnfOFSmBbNtGVFbCLfG1jDezi8TljbeHLGNXsLatMgtHm5m-UsPKoQ__&Key-Pair-Id=APKAINTVSUGEWH5XD5UA",
    };
  },
};
</script>

<template>
  <nav>
    <div class="atas">
      <div class="navbar justify-content-center ">
        <ul class="nav justify-content-center">
          <li class="nav-item">
            <a class="nav-link active link-dark" aria-current="page" href="#" style="margin-top:5px;">New Products</a>
          </li>
          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle text-dark " href="#" role="button" data-bs-toggle="dropdown"
              aria-expanded="false" style="margin-top:5px;">
              Woman
            </a>
            <ul class="dropdown-menu">
              <li><a class="dropdown-item" href="#">Best Sellers</a></li>
              <li><a class="dropdown-item" href="#">New Products</a></li>
              <li>
                <hr class="dropdown-divider">
              </li>
              <li>
                <h6 class="dropdown-item"><b>Brands</b></h6>
              </li>
              <li><a class="dropdown-item" href="#">Anna Sui</a></li>
              <li><a class="dropdown-item" href="#">Burberry</a></li>
              <li><a class="dropdown-item" href="#">Bvlgari</a></li>
              <li><a class="dropdown-item" href="#">Caia</a></li>
              <li><a class="dropdown-item" href="#">Chanel</a></li>
              <li><a class="dropdown-item" href="#">Dolce & Gabbana</a></li>
              <li><a class="dropdown-item" href="#">Elizabeth Arden</a></li>
              <li><a class="dropdown-item" href="#">Guerlain</a></li>
              <li><a class="dropdown-item" href="#">Gucci</a></li>
              <li><a class="dropdown-item" href="#">Victoria Secret</a></li>
            </ul>
          </li>
          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle text-dark" href="#" role="button" data-bs-toggle="dropdown"
              aria-expanded="false" style="margin-top:5px;">
              Man
            </a>
            <ul class="dropdown-menu">
              <li><a class="dropdown-item" href="#">Best Sellers</a></li>
              <li><a class="dropdown-item" href="#">New Products</a></li>
              <li>
                <hr class="dropdown-divider">
              </li>
              <li>
                <h6 class="dropdown-item"><b>Brands</b></h6>
              </li>
              <li><a class="dropdown-item" href="#">Abercrombie & Fitch</a></li>
              <li><a class="dropdown-item" href="#">Balenciaga</a></li>
              <li><a class="dropdown-item" href="#">Chanel</a></li>
              <li><a class="dropdown-item" href="#">Davidoff</a></li>
              <li><a class="dropdown-item" href="#">Ferrari</a></li>
              <li><a class="dropdown-item" href="#">Giorgio Armani</a></li>
              <li><a class="dropdown-item" href="#">Jaguar</a></li>
              <li><a class="dropdown-item" href="#">Prada</a></li>
              <li><a class="dropdown-item" href="#">Versace</a></li>
              <li><a class="dropdown-item" href="#">Yves Saint Laurent</a></li>
            </ul>
          </li>
          <li class="nav-item">
            <a class="nav-link link-dark" href="#" style="margin:auto;">
              <h3>D’Perfum</h3>
            </a>
          </li>
          <li class="nav-item">
            <a class="nav-link link-dark" href="#" style="margin-top:5px;">Contact Us</a>
          </li>
          <li>
            <form action="search.html" method="post" class="d-flex"
              style="margin-top: 10px; margin-left: 10px; margin-right: 10px;">
              <input type="search" name="Search" placeholder="Search">
              <div class="clearfix"></div>
            </form>
          </li>
          <li class="nav-item">
            <a class="nav-link link-dark" href="#" style="margin-top:5px;"><svg xmlns="http://www.w3.org/2000/svg"
                width="20" height="20" fill="currentColor" class="bi bi-bag" viewBox="0 0 16 16">
                <path
                  d="M8 1a2.5 2.5 0 0 1 2.5 2.5V4h-5v-.5A2.5 2.5 0 0 1 8 1zm3.5 3v-.5a3.5 3.5 0 1 0-7 0V4H1v10a2 2 0 0 0 2 2h10a2 2 0 0 0 2-2V4h-3.5zM2 5h12v9a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V5z" />
              </svg></a>
          </li>
          <li class="nav-item">
            <a class="nav-link link-dark" href="#" style="margin-top:5px;"><svg xmlns="http://www.w3.org/2000/svg"
                width="20" height="20" fill="currentColor" class="bi bi-person" viewBox="0 0 16 16">
                <path
                  d="M8 8a3 3 0 1 0 0-6 3 3 0 0 0 0 6zm2-3a2 2 0 1 1-4 0 2 2 0 0 1 4 0zm4 8c0 1-1 1-1 1H3s-1 0-1-1 1-4 6-4 6 3 6 4zm-1-.004c-.001-.246-.154-.986-.832-1.664C11.516 10.68 10.289 10 8 10c-2.29 0-3.516.68-4.168 1.332-.678.678-.83 1.418-.832 1.664h10z" />
              </svg></a>
          </li>
        </ul>
      </div>
    </div>
  </nav>


  <div class="slide">
    <div id="carouselExampleCaptions" class="carousel slide" data-bs-ride="false">
      <div class="carousel-indicators">
        <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="0" class="active"
          aria-current="true" aria-label="Slide 1"></button>
        <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="1"
          aria-label="Slide 2"></button>
        <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="2"
          aria-label="Slide 3"></button>
      </div>
      <div class="carousel-inner">
        <div class="carousel-item active">
          <img :src="titleImage1" class="d-block w-100" alt="iklan1">
          <div class="carousel-caption d-none d-md-block">
            <div class="col-lg-6">
              <div class="d-grid gap-2 d-md-flex justify-content-md-start">
                <a href="#"><button type="button" class="btn btn-primary btn-lg px-4">READ MORE</button></a>
              </div>
            </div>
          </div>
        </div>
        <div class="carousel-item">
          <img :src="titleImage2" class="d-block w-100" alt="...">
          <div class="carousel-caption d-none d-md-block">
            <div class="col-lg-6">
              <div class="d-grid gap-2 d-md-flex justify-content-md-start">
                <a href="#"><button type="button" class="btn btn-primary btn-lg px-4">READ MORE</button></a>
              </div>
            </div>
          </div>
        </div>
        <div class="carousel-item">
          <img :src="titleImage3" class="d-block w-100" alt="...">
          <div class="carousel-caption d-none d-md-block">
            <div class="col-lg-6">
              <div class="d-grid gap-2 d-md-flex justify-content-md-start">
                <a href="#"><button type="button" class="btn btn-primary btn-lg px-4">READ MORE</button></a>
              </div>
            </div>
          </div>
        </div>
        <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleCaptions"
          data-bs-slide="prev">
          <span class="carousel-control-prev-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Previous</span>
        </button>
        <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleCaptions"
          data-bs-slide="next">
          <span class="carousel-control-next-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Next</span>
        </button>
      </div>
    </div>
  </div>


  <div class="top">
    <div class="title mt-5">
      <br>
      <h2>NEW PRODUCTS</h2>
    </div>
    <div class="see">
      <a href="#">
        See all
      </a>
    </div>
    <div class="box">
      <div class="container-fluid">
        <div class="row">
          <div class="col mt-2" v-for="data in DataBarang1">
            <div class="card text-center" style="width: 18.5rem;">
              <div class="foto1">
                <img :src="data.image1" class="img-top " style="width:295px; height: 360px; margin: auto; " alt="...">
              </div>
              <div class="card-body">
                <h5 class="card-title">{{ data.nama1 }}</h5>
                <p class="card-text">{{ data.harga1 }}<br>
                  <img :src="data.rate1" class="card-img-top" style="width: 80px; height: 15px;" alt="...">
                </p>
                <a href="cart.html"><button @click="changeTitle(data)" class="btn btn-primary">
                    ADD TO CART
                  </button></a>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>

  <div class="woman">
    <div class="title">
      <br>
      <h2><b>WOMAN</b></h2>
    </div>
    <div class="see">
      <a href="#">
        See all
      </a>
    </div>
    <div class="box">
      <div class="container-fluid">
        <div class="row">
          <div class="col mt-2 " v-for="data in DataBarang2">
            <div class="card text-center" style="width: 18rem;">
              <div class="foto1">
                <img :src="data.image2" class="img-top " style="width:287px; height: 360px; " alt="...">
              </div>
              <div class="card-body">
                <h5 class="card-title">{{ data.nama2 }}</h5>
                <p class="card-text">{{ data.harga2 }}<br>
                  <img :src="data.rate2" class="card-img-top" style="width: 80px; height: 15px;" alt="...">
                </p>
                <a href="cart.html"><button @click="changeTitle(data)" class="btn btn-primary">
                    ADD TO CART
                  </button></a>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>

  <div class="man">
    <div class="title">
      <br>
      <h2><b>MAN</b></h2>
    </div>
    <div class="see">
      <a href="#">
        See all
      </a>
    </div>
    <div class="box">
      <div class="container-fluid">
        <div class="row">
          <div class="col mt-2 " v-for="data in DataBarang3">
            <div class="card text-center" style="width: 18rem;">
              <div class="foto1">
                <img :src="data.image3" class="img-top " style="width:287px; height: 360px; " alt="...">
              </div>
              <div class="card-body">
                <h5 class="card-title">{{ data.nama3 }}</h5>
                <p class="card-text">{{ data.harga3 }}<br>
                  <img :src="data.rate3" class="card-img-top" style="width: 80px; height: 15px;" alt="...">
                </p>
                <a href="cart.html"><button @click="changeTitle(data)" class="btn btn-primary">
                    ADD TO CART
                  </button></a>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>

  <div class="review">
    <div class="title mt-2">
      <br>
      <h2><b>Review</b></h2>
    </div>
    <div class="see">
      <a href="#">All Reviews
      </a>
    </div>
    <div class="box">
      <div class="container-fluid">
        <div class="row">
          <div class="col mt-2 " v-for="data in Datareview">
            <div class="card text-center" style="width: 18rem;">
              <div class="foto1">
                <img :src="data.image" class="img-top " style="width:287px; height: 360px; " alt="...">
              </div>
              <div class="card-body">
                <h5 class="card-title">{{ data.nama }}</h5>
                <p class="card-text"> <img :src="data.rate" class="card-img-top" style="width: 80px; height: 15px;"
                    alt=" ..."><br>
                  {{ data.review }}
                </p>
                <p class="card-text">{{ data.customer }}</p>
                <p class="card-text" style="color: #7e7e7e;">{{ data.tanggal }}</p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>

  <div class="bawah">
    <div class="container mt-2">
      <footer class="py-3">
        <div class="row">
          <div class="col-5 col-md-4 mb-3 ">
            <h5>CONTACT US</h5>
            <ul class="nav flex-column">
              <li class="nav-item mb-2"><svg xmlns="http://www.w3.org/2000/svg" width="16" height="16"
                  fill="currentColor" class="bi bi-envelope" viewBox="0 0 16 16">
                  <path
                    d="M0 4a2 2 0 0 1 2-2h12a2 2 0 0 1 2 2v8a2 2 0 0 1-2 2H2a2 2 0 0 1-2-2V4Zm2-1a1 1 0 0 0-1 1v.217l7 4.2 7-4.2V4a1 1 0 0 0-1-1H2Zm13 2.383-4.708 2.825L15 11.105V5.383Zm-.034 6.876-5.64-3.471L8 9.583l-1.326-.795-5.64 3.47A1 1 0 0 0 2 13h12a1 1 0 0 0 .966-.741ZM1 11.105l4.708-2.897L1 5.383v5.722Z" />
                </svg><a href="mailto:dperfum@gmail.com" class="nav-link p-0  "
                  style="color: white; ">dperfum@gmail.com</a></li>
              <li class="nav-item mb-2">
                <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor"
                  class="bi bi-telephone" viewBox="0 0 16 16">
                  <path
                    d="M3.654 1.328a.678.678 0 0 0-1.015-.063L1.605 2.3c-.483.484-.661 1.169-.45 1.77a17.568 17.568 0 0 0 4.168 6.608 17.569 17.569 0 0 0 6.608 4.168c.601.211 1.286.033 1.77-.45l1.034-1.034a.678.678 0 0 0-.063-1.015l-2.307-1.794a.678.678 0 0 0-.58-.122l-2.19.547a1.745 1.745 0 0 1-1.657-.459L5.482 8.062a1.745 1.745 0 0 1-.46-1.657l.548-2.19a.678.678 0 0 0-.122-.58L3.654 1.328zM1.884.511a1.745 1.745 0 0 1 2.612.163L6.29 2.98c.329.423.445.974.315 1.494l-.547 2.19a.678.678 0 0 0 .178.643l2.457 2.457a.678.678 0 0 0 .644.178l2.189-.547a1.745 1.745 0 0 1 1.494.315l2.306 1.794c.829.645.905 1.87.163 2.611l-1.034 1.034c-.74.74-1.846 1.065-2.877.702a18.634 18.634 0 0 1-7.01-4.42 18.634 18.634 0 0 1-4.42-7.009c-.362-1.03-.037-2.137.703-2.877L1.885.511z" />
                </svg><a href="#" class="nav-link p-0 " style="color: white;">+62 8116 2347</a>
              </li>
              <li class="nav-item mb-2">
                <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-clock"
                  viewBox="0 0 16 16">
                  <path d="M8 3.5a.5.5 0 0 0-1 0V9a.5.5 0 0 0 .252.434l3.5 2a.5.5 0 0 0 .496-.868L8 8.71V3.5z" />
                  <path d="M8 16A8 8 0 1 0 8 0a8 8 0 0 0 0 16zm7-8A7 7 0 1 1 1 8a7 7 0 0 1 14 0z" />
                </svg><a href="#" class="nav-link p-0 " style="color: white;">Monday - Saturday: 10:00 am to 5pm
                  (WIB)</a>
              </li>
            </ul>
          </div>

          <div class="col-6 col-md-2 mb-3">
            <h5>HELP</h5>
            <ul class="nav flex-column">
              <li class="nav-item mb-2"><a href="#" class="nav-link p-0 " style="color: white;">Terms of Service</a>
              </li>
              <li class="nav-item mb-2"><a href="#" class="nav-link p-0 " style="color: white;">Privacy Policy</a></li>
              <li class="nav-item mb-2"><a href="#" class="nav-link p-0 " style="color: white;">Shipping Policy</a></li>
              <li class="nav-item mb-2"><a href="#" class="nav-link p-0 " style="color: white;">Return Policy</a></li>
            </ul>
          </div>

          <div class="col-6 col-md-2 mb-3">
            <h5>SHOP</h5>
            <ul class="nav flex-column">
              <li class="nav-item mb-2"><a href="#" class="nav-link p-0 " style="color: white;">Best Sellers</a></li>
              <li class="nav-item mb-2"><a href="#" class="nav-link p-0 " style="color: white;">New Products</a></li>
              <li class="nav-item mb-2"><a href="#" class="nav-link p-0 " style="color: white;">Woman</a></li>
              <li class="nav-item mb-2"><a href="#" class="nav-link p-0 " style="color: white;">Man</a></li>
              <li class="nav-item mb-2"><a href="#" class="nav-link p-0 " style="color: white;">FAQs</a></li>
            </ul>
          </div>

          <div class="col-md-3 offset-md-1 mb-3">
            <form>
              <h5>NEWSLETTER</h5>
              <div class="d-flex flex-column  w-100 ">
                <label for="newsletter1" class="visually-hidden">Your Email</label>
                <input id="newsletter1" type="text" class="form-control" placeholder="Your Email">
                <button class="btn btn-primary" type="button">Join Us</button><br>
                <div class="col-md-5 md-1 mb-3">
                  <h5>FOLLOW US</h5>
                  <ul class="list-unstyled d-flex">
                    <li class="ms-3"><a class="link-dark" href="twitter.com"><svg xmlns="http://www.w3.org/2000/svg"
                          width="16" height="16" fill="white" class="bi bi-twitter" viewBox="0 0 16 16">
                          <path
                            d="M5.026 15c6.038 0 9.341-5.003 9.341-9.334 0-.14 0-.282-.006-.422A6.685 6.685 0 0 0 16 3.542a6.658 6.658 0 0 1-1.889.518 3.301 3.301 0 0 0 1.447-1.817 6.533 6.533 0 0 1-2.087.793A3.286 3.286 0 0 0 7.875 6.03a9.325 9.325 0 0 1-6.767-3.429 3.289 3.289 0 0 0 1.018 4.382A3.323 3.323 0 0 1 .64 6.575v.045a3.288 3.288 0 0 0 2.632 3.218 3.203 3.203 0 0 1-.865.115 3.23 3.23 0 0 1-.614-.057 3.283 3.283 0 0 0 3.067 2.277A6.588 6.588 0 0 1 .78 13.58a6.32 6.32 0 0 1-.78-.045A9.344 9.344 0 0 0 5.026 15z" />
                        </svg></a></li>
                    <li class="ms-3"><a class="link-dark" href="instagram.com"><svg xmlns="http://www.w3.org/2000/svg"
                          width="16" height="16" fill="white" class="bi bi-instagram" viewBox="0 0 16 16">
                          <path
                            d="M8 0C5.829 0 5.556.01 4.703.048 3.85.088 3.269.222 2.76.42a3.917 3.917 0 0 0-1.417.923A3.927 3.927 0 0 0 .42 2.76C.222 3.268.087 3.85.048 4.7.01 5.555 0 5.827 0 8.001c0 2.172.01 2.444.048 3.297.04.852.174 1.433.372 1.942.205.526.478.972.923 1.417.444.445.89.719 1.416.923.51.198 1.09.333 1.942.372C5.555 15.99 5.827 16 8 16s2.444-.01 3.298-.048c.851-.04 1.434-.174 1.943-.372a3.916 3.916 0 0 0 1.416-.923c.445-.445.718-.891.923-1.417.197-.509.332-1.09.372-1.942C15.99 10.445 16 10.173 16 8s-.01-2.445-.048-3.299c-.04-.851-.175-1.433-.372-1.941a3.926 3.926 0 0 0-.923-1.417A3.911 3.911 0 0 0 13.24.42c-.51-.198-1.092-.333-1.943-.372C10.443.01 10.172 0 7.998 0h.003zm-.717 1.442h.718c2.136 0 2.389.007 3.232.046.78.035 1.204.166 1.486.275.373.145.64.319.92.599.28.28.453.546.598.92.11.281.24.705.275 1.485.039.843.047 1.096.047 3.231s-.008 2.389-.047 3.232c-.035.78-.166 1.203-.275 1.485a2.47 2.47 0 0 1-.599.919c-.28.28-.546.453-.92.598-.28.11-.704.24-1.485.276-.843.038-1.096.047-3.232.047s-2.39-.009-3.233-.047c-.78-.036-1.203-.166-1.485-.276a2.478 2.478 0 0 1-.92-.598 2.48 2.48 0 0 1-.6-.92c-.109-.281-.24-.705-.275-1.485-.038-.843-.046-1.096-.046-3.233 0-2.136.008-2.388.046-3.231.036-.78.166-1.204.276-1.486.145-.373.319-.64.599-.92.28-.28.546-.453.92-.598.282-.11.705-.24 1.485-.276.738-.034 1.024-.044 2.515-.045v.002zm4.988 1.328a.96.96 0 1 0 0 1.92.96.96 0 0 0 0-1.92zm-4.27 1.122a4.109 4.109 0 1 0 0 8.217 4.109 4.109 0 0 0 0-8.217zm0 1.441a2.667 2.667 0 1 1 0 5.334 2.667 2.667 0 0 1 0-5.334z" />
                        </svg></a></li>
                    <li class="ms-3"><a class="link-dark" href="facebook.com"><svg xmlns="http://www.w3.org/2000/svg"
                          width="16" height="16" fill="white" class="bi bi-facebook" viewBox="0 0 16 16">
                          <path
                            d="M16 8.049c0-4.446-3.582-8.05-8-8.05C3.58 0-.002 3.603-.002 8.05c0 4.017 2.926 7.347 6.75 7.951v-5.625h-2.03V8.05H6.75V6.275c0-2.017 1.195-3.131 3.022-3.131.876 0 1.791.157 1.791.157v1.98h-1.009c-.993 0-1.303.621-1.303 1.258v1.51h2.218l-.354 2.326H9.25V16c3.824-.604 6.75-3.934 6.75-7.951z" />
                        </svg></a></li>
                    <li class="ms-3"><a class="link-dark" href="youtube.com"><svg xmlns="http://www.w3.org/2000/svg"
                          width="16" height="16" fill="white" class="bi bi-youtube" viewBox="0 0 16 16">
                          <path
                            d="M8.051 1.999h.089c.822.003 4.987.033 6.11.335a2.01 2.01 0 0 1 1.415 1.42c.101.38.172.883.22 1.402l.01.104.022.26.008.104c.065.914.073 1.77.074 1.957v.075c-.001.194-.01 1.108-.082 2.06l-.008.105-.009.104c-.05.572-.124 1.14-.235 1.558a2.007 2.007 0 0 1-1.415 1.42c-1.16.312-5.569.334-6.18.335h-.142c-.309 0-1.587-.006-2.927-.052l-.17-.006-.087-.004-.171-.007-.171-.007c-1.11-.049-2.167-.128-2.654-.26a2.007 2.007 0 0 1-1.415-1.419c-.111-.417-.185-.986-.235-1.558L.09 9.82l-.008-.104A31.4 31.4 0 0 1 0 7.68v-.123c.002-.215.01-.958.064-1.778l.007-.103.003-.052.008-.104.022-.26.01-.104c.048-.519.119-1.023.22-1.402a2.007 2.007 0 0 1 1.415-1.42c.487-.13 1.544-.21 2.654-.26l.17-.007.172-.006.086-.003.171-.007A99.788 99.788 0 0 1 7.858 2h.193zM6.4 5.209v4.818l4.157-2.408L6.4 5.209z" />
                        </svg></a></li>
                  </ul>
                </div>
              </div>
            </form>
          </div>
        </div>

        <div class="d-flex flex-column flex-sm-row justify-content-between  border-top">
          <p>Copyright © 2022 D’Perfum</p>
          <ul class="list-unstyled d-flex">
            <li class="ms-3">
              <p>JL Patal Senayan No. 25, Kebayoran Lama, 12210</p>
            </li>
          </ul>
        </div>
      </footer>
    </div>
  </div>
</template>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Cinzel:wght@500&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Fauna+One&display=swap');

header {
  line-height: 1.5;
}

.atas {

  font-family: 'Fauna One', serif;
}

.iklan {
  font-family: 'Cinzel', serif;
}

.iklan2 {
  background-color: #FFFCD7;
}

.title {
  text-decoration-line: underline;
  text-align: center;
  font-family: 'Cinzel', serif;
}

.see {
  text-align: end;
  margin-right: 40px;
}

.star {
  width: 100px;
  height: 10px;
}

.top {
  background-color: #ededed;
  font-family: 'Fauna One', serif;

}

.woman {
  background-color: #D9E8DD;
  font-family: 'Fauna One', serif;
}

.man {
  background-color: #CEDCDD;
  font-family: 'Fauna One', serif;
}

.review {
  font-family: 'Fauna One', serif;
}

.foto1 {
  box-shadow: 4px 4px 26px grey;
}


.bawah {
  background-color: #5C5C5C;
  color: white;
}

.slide {
  font-family: 'Fauna One', serif;
}

.row {
  font-weight: bold;
}

.box {
  margin-left: 20px;
}

.title-name {
  color: black;
  text-transform: capitalize;
}

.subtitle-name {
  color: grey;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
}

.closeButton {
  font-size: 50px;
  font-weight: bold;
  top: -40px;
  position: absolute;
  right: 0;
  cursor: pointer;
  z-index: 10;
}

.tab {
  display: inline-block;
  margin-right: 20px;
  cursor: pointer;
}

.tab:hover {
  background-color: white;
  color: hotpink;
}

.outsideContainer {
  position: absolute;
  top: 0;
  width: 100vw;
  height: 100vh;
  background-color: rgba(0, 0, 0, 0.8);
  visibility: hidden;
  opacity: 0;
  transition-property: all;
  transition-duration: 1s;
  z-index: 10;
}

.containerModal {
  background-color: white;
  padding: 20px;
  color: black;

  width: 100%;
  z-index: 10;
  width: 400px;
  height: 400px;
  margin: 40vh auto;
}

.containerModal img {
  height: 300px;
}

.outsideContainer.shown {
  visibility: visible;
  opacity: 1;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }
}

body {
  min-height: 100vh;
  color: black;
  background: white;
  transition: color 0.5s, background-color 0.5s;
  line-height: 1.6;
  font-family: Inter, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu,
    Cantarell, 'Fira Sans', 'Droid Sans', 'Helvetica Neue', sans-serif;
  font-size: 15px;
  text-rendering: optimizeLegibility;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

.btn-outline-secondary {
  --bs-btn-color: black;
  --bs-btn-border-color: black;
  --bs-btn-hover-color: #fff;
  --bs-btn-hover-bg: black;
  --bs-btn-hover-border-color: black;
  --bs-btn-focus-shadow-rgb: 108, 117, 125;
  --bs-btn-active-color: #fff;
  --bs-btn-active-bg: black;
  --bs-btn-active-border-color: black;
  --bs-btn-active-shadow: inset 0 3px 5pxrgba(0, 0, 0, 0.125);
  --bs-btn-disabled-color: black;
  --bs-btn-disabled-bg: transparent;
  --bs-btn-disabled-border-color: black;
  --bs-gradient: none;
}

.carousel-control-next,
.carousel-control-prev {
  position: absolute;
  top: 0;
  bottom: 0;
  z-index: 1;
  display: flex;
  align-items: center;
  justify-content: center;
  width: 15%;
  padding: 0;
  background-color: black;
  text-align: center;
  background: 0 0;
  border: 0;
  opacity: .5;
  transition: opacity .15s ease;
}

.btn-primary {
  text-align: center;
  --bs-btn-color: #fff;
  --bs-btn-bg: black;
  --bs-btn-border-color: black;
  --bs-btn-hover-color: #fff;
  --bs-btn-hover-bg: black;
  --bs-btn-hover-border-color: black;
  --bs-btn-focus-shadow-rgb: 49, 132, 253;
  --bs-btn-active-color: #fff;
  --bs-btn-active-bg: black;
  --bs-btn-active-border-color: black;
  --bs-btn-active-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125);
  --bs-btn-disabled-color: #fff;
  --bs-btn-disabled-bg: black;
  --bs-btn-disabled-border-color: black;
}

.btn btn-primary {
  align-items: center;
}
</style>
