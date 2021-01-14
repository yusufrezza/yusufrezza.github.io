<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Bootstrap eCommerce Page Template</title>
    <!-- Bootstrap -->
    <link href="css/bootstrap-4.3.1.css" rel="stylesheet">
  </head>
  <body>
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
      <div class="container">
        <a class="navbar-brand" href="#">Pet Shop&nbsp;</a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <ul class="navbar-nav mr-auto">
            <li class="nav-item active">
              <a class="nav-link" href="#">Beranda <span class="sr-only">(current)</span></a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Hewan&nbsp;</a>
            </li>
            <li class="nav-item dropdown">
              <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">Produk&nbsp;</a>
              <div class="dropdown-menu" aria-labelledby="navbarDropdown">
                <a class="dropdown-item" href="#">Action</a>
                <a class="dropdown-item" href="#">Another action</a>
                <div class="dropdown-divider"></div>
                <a class="dropdown-item" href="#">Something else here</a>
              </div>
            </li>
            <li class="nav-item">
              <a class="nav-link disabled" href="#">&nbsp;</a>
            </li>
          </ul>
          <form class="form-inline my-2 my-lg-0">
            <input class="form-control mr-sm-2" type="search" placeholder="Search" aria-label="Search">
            <button class="btn btn-outline-success my-2 my-sm-0" type="submit">Search</button>
          </form>
			<img src="settings.png" width="35px;"height="35px" id="cth">
        </div>
      </div>
    </nav>
    <div class="container mt-3">
      <div class="row">
        <div class="col-12">
          <div id="carouselExampleControls" class="carousel slide" data-ride="carousel">
            <ol class="carousel-indicators">
              <li data-target="#carouselExampleControls" data-slide-to="0" class="active"></li>
              <li data-target="#carouselExampleControls" data-slide-to="1"></li>
              <li data-target="#carouselExampleControls" data-slide-to="2"></li>
            </ol>
            <div class="carousel-inner">
              <div class="carousel-item active"> <center>
                <img class="d-block w-100" src="gambar1.jpg" height="626px" width="200px" alt="First slide">
                <div class="carousel-caption d-none d-md-block">
                
                </div>
				  
              </div>
				  </center>
              <div class="carousel-item">
                <img class="d-block w-100" src="Logo petshop.jpg" alt="Second slide">
                <div class="carousel-caption d-none d-md-block">
                  
                </div>
              </div>
              <div class="carousel-item">
                <img class="d-block w-100" src="Gambar Slide 3.jpg" alt="Third slide">
                <div class="carousel-caption d-none d-md-block">
                  
                </div>
              </div>
            </div>
            <a class="carousel-control-prev" href="#carouselExampleControls" role="button" data-slide="prev">
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="sr-only">Previous</span>
            </a>
            <a class="carousel-control-next" href="#carouselExampleControls" role="button" data-slide="next">
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="sr-only">Next</span>
            </a>
          </div>
        </div>
      </div>
      <hr>
    </div>
    <div class="container">
      <div class="row">
        <div class="col-4">
          <div class="row">
            <div class="col-2"><img class="rounded-circle" alt="Free Shipping" src="delivery-truck.png" height="40px" width="40px"></div>
            <div class="col-lg-6 col-10 ml-1">
              <h4>Free Deliver Pet&nbsp;</h4>
            </div>
          </div>
        </div>
        <div class="col-4">
          <div class="row">
            <div class="col-2"><img class="rounded-circle" alt="Free Shipping" src="box.png" height="40px" width="40px"></div>
            <div class="col-lg-6 col-10 ml-1">
              <h4>Free Returns</h4>
            </div>
          </div>
        </div>
        <div class="col-4">
          <div class="row">
            <div class="col-2"><img class="rounded-circle" alt="Free Shipping" src="pet.jpg" height="40px" width="40px"></div>
            <div class="col-lg-6 col-10 ml-1">
              <h4>Healthy Pet&nbsp; &nbsp;</h4>
            </div>
          </div>
        </div>
      </div>
    </div>
    <hr>
    <h2 class="text-center">FEATURED CATS&nbsp;</h2>
    <hr>
    <div class="container">
      <div class="row text-center">
        <div class="col-md-4 pb-1 pb-md-0">
          <div class="card">
            <img class="card-img-top" src="kucing1.jpg" width="400" height="200" alt="Card image cap">
            <div class="card-body">
              <h5 class="card-title">Persia&nbsp;</h5>
              <p class="card-text">Kucing persia adalah kucing domestik berbulu panjang dengan wajah bulat dan moncong pendek. Ia sangat manja dan selalu ingin menempel dengan pemiliknya namun cenderung tenang</p>
              <a href="#" class="btn btn-primary">Adopsi!</a>
            </div>
          </div>
        </div>
        <div class="col-md-4 pb-1 pb-md-0">
          <div class="card">
            <img class="card-img-top" src="kucing2.jpg" width="400" height="200" alt="Card image cap">
            <div class="card-body">
              <h5 class="card-title">Sphynx</h5>
              <p class="card-text">Kucing sphynx adalah salah satu ras kucing yang memiliki bulu sangat pendek dan sedikit sekali. Meskipun terlihat, namun kucing ini adalah ras kucing paling penyayang dibanding ras lainnya.</p>
              <a href="#" class="btn btn-primary">Adopsi!</a>
            </div>
          </div>
        </div>
        <div class="col-md-4 pb-1 pb-md-0">
          <div class="card">
            <img class="card-img-top" src="bengal.jpg" width="400" height="200" alt="Card image cap">
            <div class="card-body">
              <h5 class="card-title">Bengal</h5>
              <p class="card-text">Kucing bengal memiliki pola bulu seperti macan tutul dan terlihat seperti hewan liar, namun tidak dengan sifatnya. Kucing ini sangat aktif, cerdas, dan setia dengan pemiliknya.</p>
              <a href="#" class="btn btn-primary">Adopsi!</a>
            </div>
          </div>
        </div>
      </div>
      <div class="row text-center mt-4">
        <div class="col-md-4 pb-1 pb-md-0">
          <div class="card">
            <img class="card-img-top" src="kucing4.jpg" width="400" height="200" alt="Card image cap">
            <div class="card-body">
              <h5 class="card-title">Maine Coon&nbsp;</h5>
              <p class="card-text">Kucing Maine Coon memiliki tubuh yang besar dan bulu yang tebal sehingga dapat beradaptasi pada suhu ekstrim. Uniknya, Maine Coon suka dengan air, tetapi takut dengan ketinggian</p>
              <a href="#" class="btn btn-primary">Adopsi!</a>
            </div>
          </div>
        </div>
        <div class="col-md-4 pb-1 pb-md-0">
          <div class="card">
            <img class="card-img-top" src="kucing5.jpg" width="400" height="200" alt="Card image cap">
            <div class="card-body">
              <h5 class="card-title">British Shorthair&nbsp;&nbsp;</h5>
              <p class="card-text">Kucing British Shorthair memiliki bentuk badan yang cukup besar dan seringkali dianggap boneka beruang dalam dunia kucing. Ia sangat mudah beradaptasi dengan manusia dan memilki sifat tenang dan penyayang</p>
              <a href="#" class="btn btn-primary">Adopsi!</a>
            </div>
          </div>
        </div>
        <div class="col-md-4 pb-1 pb-md-0">
          <div class="card">
            <img class="card-img-top" src="kucing6.jpg" width="400" height="200" alt="Card image cap">
            <div class="card-body">
              <h5 class="card-title">Siam</h5>
              <p class="card-text">Kucing Siam identik dengan bulu pada muka yang lebih gelap dibandingkan bulu badannya. Ia sangat suka mengoceh namun sangat cerdas. Kucing ini sangat terikat dengan majikannya dan bisa depresi jika ditinggal sendiri.</p>
              <a href="#" class="btn btn-primary">Adopsi!</a>
            </div>
          </div>
        </div>
      </div>
    </div>
	   <hr>
    <h2 class="text-center">FEATURED DOGS&nbsp;</h2>
    <hr>
    <div class="container">
      <div class="row text-center">
        <div class="col-md-4 pb-1 pb-md-0">
          <div class="card">
            <img class="card-img-top" src="Anjing1.jpg" width="400" height="200" alt="Card image cap">
            <div class="card-body">
              <h5 class="card-title">Akita&nbsp;</h5>
              <p class="card-text">Anjing Akita atau akita ini yang merupakan anjing asli Jepang.
Meski imut, sebenarnya akita juga banyak dimanfaatkan sebagai
teman berburu karena kelincahan dan kemampuannya melacak.</p>
              <a href="#" class="btn btn-primary">Adopsi!</a>
            </div>
          </div>
        </div>
        <div class="col-md-4 pb-1 pb-md-0">
          <div class="card">
            <img class="card-img-top" src="anjing2.jpg" width="400" height="200" alt="Card image cap">
            <div class="card-body">
              <h5 class="card-title">Beagle&nbsp;</h5>
              <p class="card-text">Anjing jenis beagle memiliki tubuh yang mungil dibandingkan anjing jenis lain.
Telinganya lebar dan panjang.</p>
              <a href="#" class="btn btn-primary">Adopsi!</a>
            </div>
          </div>
        </div>
        <div class="col-md-4 pb-1 pb-md-0">
          <div class="card">
            <img class="card-img-top" src="anjing8.jpg" width="400" height="200" alt="Card image cap">
            <div class="card-body">
              <h5 class="card-title">Pekingese&nbsp;</h5>
              <p class="card-text">Pekingese memiliki tubuh yang mungil berorot dan berat. Bulu yang lebat membuat anjing ini telihat cantik.
Cenderung susah diajari karena sifatnya yang keras kepala.</p>
              <a href="#" class="btn btn-primary">Adopsi!</a>
            </div>
          </div>
        </div>
      </div>
      <div class="row text-center mt-4">
        <div class="col-md-4 pb-1 pb-md-0">
          <div class="card">
            <img class="card-img-top" src="anjing6.jpg" width="400" height="200" alt="Card image cap">
            <div class="card-body">
              <h5 class="card-title">ShibaInu</h5>
              <p class="card-text">ShibaInu merupakan anjing ras paling populer di Jepang.
Bersifat cenderung agresif dan tempramental.</p>
              <a href="#" class="btn btn-primary">Adopsi!</a>
            </div>
          </div>
        </div>
        <div class="col-md-4 pb-1 pb-md-0">
          <div class="card">
            <img class="card-img-top" src="anjing9.jpg" width="400" height="200" alt="Card image cap">
            <div class="card-body">
              <h5 class="card-title">Golden Retriever&nbsp;&nbsp;</h5>
              <p class="card-text">Anjing golden retriever merupakan anjing terpintar di dunia.
Memiliki sifat penyayang, penyabar, dan setia.
Golden retriever juga dikenal memiliki penciuman yang tajam sehingga tak jarang dijadikan teman berburu.</p>
              <a href="#" class="btn btn-primary">Adopsi!</a>
            </div>
          </div>
        </div>
        <div class="col-md-4 pb-1 pb-md-0">
          <div class="card">
            <img class="card-img-top" src="anjing10.jpg" width="400" height="200" alt="Card image cap">
            <div class="card-body">
              <h5 class="card-title">Alaskan Malamute</h5>
              <p class="card-text">Anjing alaskan malamute ini merupakan anjing yang mirip dengan serigala.
Tubuhnya berbulu tebal, cerdas, mandiri, dan setia.</p>
              <a href="#" class="btn btn-primary">Adopsi!</a>
            </div>
          </div>
        </div>
      </div>
    </div>
    <hr>
    <h2 class="text-center">CATS NEEDS&nbsp;</h2>
    <hr>
    <div class="container">
      <div class="row">
        <div class="col-lg-4">
          <ul class="list-unstyled">
            <li class="media">
              <img class="mr-3" src="whiskas.jpg" width="100" height="125" alt="Generic placeholder image">
              <div class="media-body">
                <h5 class="mt-0 mb-1">Whiskas Dry Food Tuna Flavour&nbsp;</h5>
                Mengandung Omega 3 & 6 , serta Zinc untuk kesehatan kulit dan bulu yang indah. Mengandung Vit.A dan taurine untuk kesehatan matanya. Mengandung protein dari ikan yang segar, lemak yang baik, vitamin dan mineral yang seimbang, untuk tetap menjaga kucingmu aktif dan bahagia.
              </div>
            </li>
            <li class="media my-4">
              <img class="mr-3" src="rc.jpg" width="100" height="125" alt="Generic placeholder image">
              <div class="media-body">
                <h5 class="mt-0 mb-1">Royal Canin Dry Food</h5>
                Untuk Persian Kitten. Pertumbuhan rambut yang sehat dan panjang. Melancarkan kinerja pencernaan. Menunjang sistem kekebalan tubuh
              </div>
            </li>
            <li class="media">
              <img class="mr-3" src="meo.jpg" width="100" height="125" alt="Generic placeholder image">
              <div class="media-body">
                <h5 class="mt-0 mb-1">Me-O Dry Food</h5>
                Mengandung Taurin untuk asam amino yang sangat penting untuk berfungsinya mata dan meningkatkan penglihatan. Vitamin C Untuk sistem kekebalan tubuh kucing kucing dan membantu mengurangi efek stress. Kalsium, Fosfor dan Vitamin D untuk Membantu memperkuat gigi dan tulang 
              </div>
            </li>
          </ul>
        </div>
        <div class="col-lg-4">
          <ul class="list-unstyled">
            <li class="media">
              <img class="mr-3" src="whiskas2.jpg" width="100" height="125" alt="Generic placeholder image">
              <div class="media-body">
                <h5 class="mt-0 mb-1">Whiskas Wet Food Tuna Flavour&nbsp;</h5>
                Spesifik diformulasikan untuk kucing usia 1 tahun keatas. Mengandung Omega 3 & 6 , serta Zinc untuk kesehatan kulit dan bulu yang indah. Mengandung Vit.A dan taurine untuk kesehatan matanya. Mengandung protein dari ikan yang segar, lemak yang baik, vitamin dan mineral yang seimbang, untuk tetap menjaga kucingmu aktif dan bahagia. Mengandung Antioksidan (Vit E dan Selenium ) untuk kesehatan sistem immunnya.
              </div>
            </li>
            <li class="media my-4">
              <img class="mr-3" src="rc2.jpg" width="100" height="125" alt="Generic placeholder image">
              <div class="media-body">
                <h5 class="mt-0 mb-1">Royal Canin Wet Food</h5>
                Royal Canin Wet Food (Instinctive). Memenuhi selera makan kucing. Sistem saluran kemih yang sehat. Menjaga berat badan yang ideal.
              </div>
            </li>
            <li class="media">
              <img class="mr-3" src="meo2.jpg" width="100" height="125" alt="Generic placeholder image">
              <div class="media-body">
                <h5 class="mt-0 mb-1">Me-O Wet Food</h5>
                Mengandung Vitamin E untuk membantu untuk memperkuat sistem kekebalan tubuh. Omega 3&6 and Zinc dari minyak ikan berkualitas tinggi dikombimasikan dengan Zinc akan membantu melembutkan kulit dan bulu kucing. Protein dari daging berkualitas memberikan asam amino yang penting untuk menjaga masa otot yang baik
              </div>
            </li>
          </ul>
        </div>
        <div class="col-lg-4">
          <ul class="list-unstyled">
            <li class="media">
              <img class="mr-3" src="mainan.jpg" width="100" height="125" alt="Generic placeholder image">
              <div class="media-body">
                <h5 class="mt-0 mb-1">Mainan Tongkat Kucing Bulu</h5>
               Mainan Tongkat Kucing
Bulu terbuat dari bulu sintetis, kuat dan tidak mudah rontok.
Cocok untuk bermain dengan kucing kesayangan Anda. 
              </div>
            </li>
            <li class="media my-4">
              <img class="mr-3" src="kalung.jpg" width="100" height="125" alt="Generic placeholder image">
              <div class="media-body">
                <h5 class="mt-0 mb-1">Kalung Kucing Berlonceng</h5>
                Kalung Kucing dengan Lonceng.
Bahan Kanvas (dapat menyerap air).
Ukuran bisa disesuaikan dengan leher kucing.
              </div>
            </li>
            <li class="media">
              <img class="mr-3" src="kandangkucing.jpg" width="100" height="125" alt="Generic placeholder image">
              <div class="media-body">
                <h5 class="mt-0 mb-1">Kandang 3 tingkat</h5>
                Kandang Kucing 3 Tingkat, Tahan Air.
Bahan Alumunium Anti Karat
              </div>
            </li>
          </ul>
        </div>
      </div>
    </div>
	      <hr>
    <h2 class="text-center">DOGS NEEDS&nbsp;</h2>
    <hr>
    <div class="container">
      <div class="row">
        <div class="col-lg-4">
          <ul class="list-unstyled">
            <li class="media">
              <img class="mr-3" src="makanan1.jpg" width="100" height="125" alt="Generic placeholder image">
              <div class="media-body">
                <h5 class="mt-0 mb-1">Pedigree&nbsp;</h5>
                Dog food terbaik yang pertama adalah buatan Pedigree.
Makanan anjing ini memiliki kandungan esensial untuk kesehatan peliharaanmu,
karena mengandung minyak nabati yang menjadi sumber asam linoleat yang akan berguna untuk menyehatkan kulit serta memberikan kilau indah pada bulu anjingmu.
Selain itu, ada juga buah bit yang menjadi sumber serat yang berguna untuk membantu pencernaan hewan kesayanganmu.
              </div>
            </li>
            <li class="media my-4">
              <img class="mr-3" src="makanan2.png" width="100" height="125" alt="Generic placeholder image">
              <div class="media-body">
                <h5 class="mt-0 mb-1">Science Diet</h5>
                Anjing kamu layak mendapat makanan yang lezat dan bergizi.
Maka dari itu, Science Diet membuat makanan anjing menggunakan bahan-bahan berkualitas tinggi termasuk ayam, daging domba, dan salmon.
Tidak hanya masing-masing bahan yang diperiksa untuk memastikan kualitasnya,
makanan hewan Science Diet juga menganalisis profil bahan setiap produk untuk nutrisi pentingnya dan memastikan hewan peliharaan kamu mendapatkan formulasi yang tepat sesuai dengan yang mereka butuhkan.
              </div>
            </li>
            <li class="media">
              <img class="mr-3" src="makanan3.jpg" width="100" height="125" alt="Generic placeholder image">
              <div class="media-body">
                <h5 class="mt-0 mb-1">Royal Canin</h5>
                Memformulasikan makanan hewan peliharaan premium terbaik di dunia bukanlah
tugas yang mudah. Setiap formula makanan-makanan anjing yang
dibuat oleh Royal Canin terdiri dari lebih dari 50 nutrisi yang harus dimasukkan
dalam makanan anjing kamu demi keseimbangan yang tepat untuk memasok nutrisi yang paling efektif untuk anjing dengan berbagai ukuran, usia, dan  keturunan dengan kebutuhan khusus.
              </div>
            </li>
          </ul>
        </div>
        <div class="col-lg-4">
          <ul class="list-unstyled">
            <li class="media">
              <img class="mr-3" src="makanan4.jpg" width="100" height="125" alt="Generic placeholder image">
              <div class="media-body">
                <h5 class="mt-0 mb-1">Pro Plan&nbsp;</h5>
                Dog food terbaik buatan Pro Plan dibuat dengan kepercayaan bahwa kehidupan
terbaik dari hewan peliharaan kamu dimungkinkan melalui kekuatan nutrisi yang
didapatnya. Pro Plan berusaha untuk membantu anjing kamu menjadi lebih energik
dan tangguh, dengan tetap menjaga kondisi tubuh ideal, kulit yang sehat,
dan juga mantel yang menakjubkan di setiap tahap kehidupan.
Makanan hewan ini membantu anjing peliharaanmu mendapatkan asupan tepat meski
memiliki kebutuhan yang lebih variatif.
              </div>
            </li>
            <li class="media my-4">
              <img class="mr-3" src="makanan5.jpg" width="100" height="125" alt="Generic placeholder image">
              <div class="media-body">
                <h5 class="mt-0 mb-1">Alpo</h5>
                Makanan anjing Alpo sesuai dengan diet anjing anjing peliharaan kamu karena
memiliki rasa dan aroma daging yang kuat yang digemari para anjing.
Makanan buatan Alpo terdiri dari sumber protein yang memiliki kualitas
tinggi dan juga diformulasikan dengan 23 jenis vitamin dan mineral esensial
yang sangat penting agar anjing peliharaanmu selalu sehat, bahagia, dan berumur panjang.
              </div>
            </li>
            <li class="media">
              <img class="mr-3" src="makanan6.jpg" width="100" height="125" alt="Generic placeholder image">
              <div class="media-body">
                <h5 class="mt-0 mb-1">Jerhigh</h5>
                Makanan anjing Jerhigh terbuat dari daging ayam asli dengan standar kualitas yang
sama dengan makanan manusia dan memiliki rasa yang enak sesuai dengan selera anjing
peliharaanmu. Makanan anjing merek ini juga memiliki nutrisi-nutrisi yang penting
agar anjing milikmu berumur lebih panjang dan juga kesehatan yang ideal.

              </div>
            </li>
          </ul>
        </div>
        <div class="col-lg-4">
          <ul class="list-unstyled">
            <li class="media">
              <img class="mr-3" src="Kandang.jpg" width="100" height="125" alt="Generic placeholder image">
              <div class="media-body">
                <h5 class="mt-0 mb-1">Kandang Anjing Bahan Kayu Solid Anti Air</h5>
               Bahan : Kayu
Suitable size: high-end version 
              </div>
            </li>
            <li class="media my-4">
              <img class="mr-3" src="Tali.jpg" width="100" height="125" alt="Generic placeholder image">
              <div class="media-body">
                <h5 class="mt-0 mb-1">Tali</h5>
                Dapat digunakan pada anjing besar maupun kecil.
Bahan Nylon dan Hook Besi.
Panjang 125cm.
Diameter tali : 1.
3cm.
Tebal Hook: 8cm
              </div>
            </li>
            <li class="media">
              <img class="mr-3" src="Kasur.jpg" width="100" height="125" alt="Generic placeholder image">
              <div class="media-body">
                <h5 class="mt-0 mb-1">Kasur</h5>
                Tempat tidur anjing ukuran XXL (Panjang 90 x Lebar 65 cm) untuk berat s/d 35 Kg Golden, Husky dll.
              </div>
            </li>
          </ul>
        </div>
      </div>
    </div>
    <hr>
    <div class="container text-white bg-dark p-4">
      <div class="row">
        <div class="col-6 col-md-8 col-lg-7">
          <div class="row text-center">
            <div class="col-sm-6 col-md-4 col-lg-4 col-12">
              <ul class="list-unstyled">
                <li class="btn-link"> <a>Link anchor</a> </li>
                <li class="btn-link"> <a>Link anchor</a> </li>
                <li class="btn-link"> <a>Link anchor</a> </li>
                <li class="btn-link"> <a>Link anchor</a> </li>
                <li class="btn-link"> <a>Link anchor</a> </li>
              </ul>
            </div>
            <div class="col-sm-6 col-md-4 col-lg-4 col-12">
              <ul class="list-unstyled">
                <li class="btn-link"> <a>Link anchor</a> </li>
                <li class="btn-link"> <a>Link anchor</a> </li>
                <li class="btn-link"> <a>Link anchor</a> </li>
                <li class="btn-link"> <a>Link anchor</a> </li>
                <li class="btn-link"> <a>Link anchor</a> </li>
              </ul>
            </div>
            <div class="col-sm-6 col-md-4 col-lg-4 col-12">
              <ul class="list-unstyled">
                <li class="btn-link"> <a>Link anchor</a> </li>
                <li class="btn-link"> <a>Link anchor</a> </li>
                <li class="btn-link"> <a>Link anchor</a> </li>
                <li class="btn-link"> <a>Link anchor</a> </li>
                <li class="btn-link"> <a>Link anchor</a> </li>
              </ul>
            </div>
          </div>
        </div>
        <div class="col-md-4 col-lg-5 col-6">
          <address>
            <strong>Pet Shop&nbsp;</strong><br>
            Jl. Jakarta Raya, Bekasi<br>
            Dodit, WA, 0896-5485-8281<br>
            <abbr title="Phone">P:</abbr> (021) 880-7890
          </address>
          <address>
            <strong>Dodit Wibowo&nbsp;</strong><br>
            <a href="mailto:#">Doditkece@gmail.com&nbsp;</a>
          </address>
        </div>
      </div>
    </div>
    <footer class="text-center">
      <div class="container">
        <div class="row">
          <div class="col-12">
            <p>Copyright © MyWebsite. All rights reserved.</p>
          </div>
        </div>
      </div>
    </footer>
    <!-- jQuery (necessary for Bootstrap's JavaScript plugins) -->
    <script src="js/jquery-3.3.1.min.js"></script>
    <!-- Include all compiled plugins (below), or include individual files as needed -->
    <script src="js/popper.min.js"></script>
    <script src="js/bootstrap-4.3.1.js"></script>
  </body>
</html>
