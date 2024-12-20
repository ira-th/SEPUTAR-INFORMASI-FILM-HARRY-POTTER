<!DOCTYPE html>
<html lang="id">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SEPUTAR INFORMASI FILM HARRY POTTER</title>
    <style>
        body {
            font-family: "HighTowerText", serif;
            font-size: large;
            margin: 0;
            padding: 0;
            padding-bottom: 50px;
            background-image: url('images wp/hogwarts-harry-1920x1200-13694.jpg');
            background-size: cover; /* Agar gambar memenuhi layar */
            background-attachment: fixed; /* Agar background tidak bergerak saat di-scroll */
            background-position:top; /* Posisikan di tengah */
            background-repeat: no-repeat;
            overflow-x: hidden;
        }

        /* Navbar */
        nav {
            background-color: #a43521;
            display: flex;
            justify-content: space-between;
            padding: 15px;
            position: sticky;
            top: 0;
            z-index: 800;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            font-family: 'Bodoni MT Black', serif;
            font-size:x-large;
        }

        nav ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
            display: flex;
        }

        nav ul li {
            margin-right: 20px;
        }

        nav ul li a {
            text-decoration: none;
            color: white;
            font-weight: bold;
        }

        nav ul li a:hover {
            color: #cc796a;
        }

        /* Header */
        header {
            background: linear-gradient(to right, #a43521, #a43521);
            color: white;
            text-align: center;
            padding: 20px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            border-bottom: 4px solid #cc796a;
            font-family: 'Elephant', serif;

        }

        /* Header baru dengan gambar besar */
        .big-header {
            background-color: #a43521;
            text-align: center;
            padding: 20px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }

        .big-header img {
            width: 100%;
            height: auto;
            object-fit: contain;
            border-radius: 15px;
            opacity: 1;
        }

        /* Layout Tiga Kolom */
        .container {
            display: flex;
            justify-content: center;
            gap: 15px;
            padding: 20px;
            margin-top: 20px;
        }

        .content {
            background: linear-gradient(to bottom, #a43521 , #fe8888 );
            padding: 20px;
            width: 60%;
            margin: 10px;
            border-radius: 15px;
            box-shadow: 0 6px 12px rgba(0, 0, 0, 0.3);
            font-family: 'Elephant', serif;
        }

        .content:hover {
            transform: scale(1.02);
        }

        .sidebar-left {
            background-color: #f69483;
            padding: 20px;
            width: 30%;
            margin: 10px;
            border-radius: 15px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            font-family: 'Bookman Old Style', serif;
        
        }
        .sidebar-right {
            background-color: #f69483;
            padding: 20px;
            width: 20%;
            margin: 10px;
            border-radius: 15px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            font-family: 'Bookman Old Style', serif;
            }

        /* Gaya untuk Gambar */
        .image-film {
            display: block;
            margin: 10px auto;
            max-width: 30%;
            height: auto;
            border-radius: 15px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.3);
        }

        #beranda img {
            display: block;
            margin: 20px auto;
            max-width: 80%;
            height: auto;
            border-radius: 15px;
            box-shadow: 0 6px 12px rgba(0, 0, 0, 0.3);
            border: 5px solid #a43521;
        }

        /* Footer */
        footer {
            background-color: #a43521;
            color: white;
            text-align: center;
            padding: 10px;
            position: fixed;
            bottom: 0;
            width: 100%;
            box-shadow: 0 -2px 8px rgba(0, 0, 0, 0.2);
        }

        /* Tombol Tampilkan/Sembunyikan */
        .toggle-button {
            background-color: #a43521;
            color: white;
            border: none;
            padding: 10px;
            border-radius: 5px;
            cursor: pointer;
            margin-top: 10px;
        }

        .toggle-button:hover {
            background-color: #f57660 ;
        }

        .hidden {
            display: none;
        }

        /* Gaya untuk video */
                .video-film {
            display: block;
            margin: 20px auto;
            max-width: 100%;
            height: auto;
            border-radius: 15px;
            box-shadow: 0 6px 12px rgba(0, 0, 0, 0.3);
            border: 5px solid #f57660;
        }

        /* Adjust image sizes for images 3 to 7 */
        #film-harry-potter img {
            display: block;
            margin: 10px auto;
            max-width: 30%; /* Adjust width to 60% */
            height: auto;
            border-radius: 15px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.3);
        }
        /* Pengaturan umum untuk gambar */
        img {
            max-width: 100%;        /* Membuat gambar responsif agar tidak lebih lebar dari kontainer */
            height: auto;          /* Menjaga rasio aspek gambar */
            border-radius: 8px;    /* Memberikan sedikit radius untuk sudut gambar */
            display: block;        /* Menghilangkan spasi bawah gambar */
            margin-bottom: 15px;   /* Memberikan jarak di bawah gambar */
        }

        /* Mengatur gambar khusus untuk sidebar kiri */
        .sidebar-left img {
            max-width: 60%;         /* Membatasi lebar gambar di sidebar */
            margin: 10px auto;      /* Memberikan margin di atas dan bawah gambar */
            display: block;         /* Menyusun gambar menjadi blok */
        }

        /* Memberikan efek hover pada gambar */
        img:hover {
            opacity: 0.8;           /* Mengurangi opacity saat gambar di-hover */
            transition: opacity 0.3s ease;  /* Transisi halus untuk efek hover */
        }

        /* Menambahkan padding dan margin pada kontainer */
        .container {
            display: flex;
            justify-content: space-between;
            gap: 20px;
            padding: 20px;
        }

    </style>
</head>

    <!-- Navbar -->
    <nav>
        <ul>
            <li><a href="#beranda">Beranda</a></li>
            <li><a href="#film-harry-potter">Film</a></li>
            <li><a href="#karakter-utama">Karakter Utama</a></li>
            <li><a href="#trivia-fakta-menarik">Trivia & Fakta Menarik</a></li>
            <li><a href="#akhir-kata">Akhir Kata</a></li>
        </ul>
    </nav>

    <!-- Header baru dengan gambar besar -->
    <div class="big-header">
        <img src="images wp/harry-potter-wallpaper-harry-potter-images-4k.jpg" alt="Gambar Besar Harry Potter">
    </div>

    <!-- Header utama -->
    <header>
        <h1>SEPUTAR INFORMASI FILM HARRY POTTER</h1>
    </header>

    <!-- Container untuk Tiga Kolom -->
    <div class="container">
        <!-- Sidebar Kiri -->
        <aside class="sidebar-left">
            <h3>Nominasi dan Penghargaan</h3>
            <p id="left-content" class="hidden">
                Franchise Harry Potter mendapatkan banyak nominasi dan penghargaan selama bertahun-tahun, terutama untuk aspek teknis, visual, dan akting. Berikut beberapa penghargaan dan nominasi penting yang diterima film-film Harry Potter:
                <br><br>
                1. <b>Academy Awards (Oscar)</b>
                <br> Harry Potter and the Sorcerer’s Stone (2001) dinominasikan untuk Best Art Direction, Best Costume Design, dan Best Original Score.
                <br>- Harry Potter and the Goblet of Fire (2005) dinominasikan untuk Best Art Direction.
                <br>- Harry Potter and the Deathly Hallows – Part 2 (2011) mendapatkan tiga nominasi Oscar, yaitu Best Art Direction, Best Visual Effects, dan Best Makeup.
                <br><br>
                2. <b>British Academy Film Awards (BAFTA)</b>
                <br> Hampir setiap film dalam franchise ini dinominasikan di BAFTA untuk berbagai kategori teknis seperti Best Special Visual Effects, Best Production Design, dan Best Makeup and Hair.
                <br>- Harry Potter and the Deathly Hallows – Part 2 memenangkan Outstanding British Contribution to Cinema di BAFTA pada 2011 sebagai penghargaan untuk keseluruhan seri film.
                <br><br>
                3. <b>Saturn Awards</b>
                <br> -Harry Potter and the Prisoner of Azkaban (2004) memenangkan Best Fantasy Film dan mendapatkan beberapa nominasi, termasuk untuk Best Director (Alfonso Cuarón).
                <br> - Harry Potter and the Deathly Hallows – Part 2 memenangkan Best Fantasy Film pada 2012 dan beberapa nominasi untuk efek khusus dan akting.
                <br><br>
                4. <b>Art Directors Guild Awards</b>
                <br>-Beberapa film Harry Potter memenangkan penghargaan di kategori Excellence in Production Design, termasuk Harry Potter and the Deathly Hallows – Part 2.
                <br><br>
                5. <b>Visual Effects Society Awards</b>
                <br> -Harry Potter and the Deathly Hallows – Part 2 memenangkan Outstanding Visual Effects in a Visual Effects-Driven Feature Motion Picture dan penghargaan lain untuk keunggulan teknis dalam efek visual.
                <br><br>
                6. <b>MTV Movie Awards</b>
                <br>-Serial ini banyak memenangi kategori populer seperti Best Villain (Ralph Fiennes sebagai Voldemort) dan Best Hero (Daniel Radcliffe sebagai Harry Potter).
                <br><br>
                7. <b>Grammy Awards</b>
                <br>-Soundtrack Harry Potter and the Sorcerer’s Stone karya John Williams dinominasikan untuk Best Score Soundtrack for Visual Media pada Grammy Awards.
                <br><br>
                Meskipun tidak selalu membawa pulang penghargaan tertinggi, seri Harry Potter tetap menjadi salah satu franchise paling dihormati dalam dunia perfilman, terutama untuk kontribusi dalam hal visual, efek, dan produksi.
            </p>
            <button id="toggle-left" class="toggle-button" onclick="toggleContent('left-content', 'toggle-left')">Tampilkan</button>
            <h2>Beberapa artis yang terkait!</h2>
            <br>Berikut adalah beberapa artis utama yang terlibat dalam film Harry Potter:
            <br>1. <b>Daniel Radcliffe sebagai Harry Potter</b>
            <img class="image-film" src="https://th.bing.com/th/id/R.a4947b9d2c58f46bd43ce8e0aad51956?rik=eJRLYwhqmo8TWg&riu=http%3a%2f%2fimages1.fanpop.com%2fimages%2fphotos%2f2000000%2fHarry-Potter-daniel-radcliffe-2083478-1508-2100.jpg&ehk=CetkDbmEcNZtiqRV%2bq12QxGzoKQgF6Fp3XKfvIwCvag%3d&risl=&pid=ImgRaw&r=0" alt="Harry Potter Film 1">
               <br>Aktor utama dalam seri ini, berperan sebagai penyihir muda yang berjuang melawan Voldemort.
            
           <br> 2. <b>Rupert Grint sebagai Ron Weasley </b>
               <br><img class="image-film" src="https://th.bing.com/th/id/OIP.m4_i4_HsEouVonS6DpSVdQHaKO?rs=1&pid=ImgDetMain" alt="Harry Potter Film 1">
               Teman dekat Harry Potter, berasal dari keluarga Weasley yang besar dan penuh kasih.
               
           <br>3. <b>Emma Watson sebagai Hermione Granger  </b>
               <br><img class="image-film" src="https://th.bing.com/th/id/OIP.5JUPl3pWyPROXgvE5GB23wHaJE?rs=1&pid=ImgDetMain" alt="Harry Potter Film 1">
               Sahabat terbaik Harry dan Ron, dikenal dengan kecerdasannya serta kecintaan terhadap belajar.
            
           <br> 4. <b>Richard Harris (Harry Potter 1 & 2) dan Michael Gambon (Harry Potter 3-8) sebagai Albus Dumbledore </b>
               <br><br><img class="image-film" src="https://th.bing.com/th/id/OIP.oGnJZSrn1vO5AB-Uu0KLAQAAAA?rs=1&pid=ImgDetMain" alt="Harry Potter Film 1">
               Kepala Sekolah Hogwarts yang bijaksana dan mentor bagi Harry.
            
           <br> 5. <b>Alan Rickman sebagai Severus Snape</b> 
               <br><br><img class="image-film" src="https://th.bing.com/th/id/OIP.5D1wCv8k76y-8Mtc4wlliwHaFj?rs=1&pid=ImgDetMain" alt="Harry Potter Film 1">
               Guru Sihir Pertahanan Terhadap Ilmu Hitam yang misterius dan penuh konflik.
            
           <br> 6. <b>Maggie Smith sebagai Minerva McGonagall</b>
               <br> <br><img class="image-film" src="https://upload.wikimedia.org/wikipedia/en/e/ea/McGonagall_%28screenshot%29.jpg" alt="Harry Potter Film 1">
               Guru Transfigurasi dan Wakil Kepala Sekolah Hogwarts yang tegas namun penyayang.
            
           <br> 7. <b>Tom Felton sebagai Draco Malfoy </b>
               <br><br><img class="image-film" src="https://th.bing.com/th/id/R.37bd4d0b6fd1ada409c0614ad454a209?rik=76kjVreZX0oEww&riu=http%3a%2f%2fvignette4.wikia.nocookie.net%2fharrypotter%2fimages%2f8%2f83%2fTom_Felton_as_Draco_Malfoy_(GoF-promo-02).jpg%2frevision%2flatest%3fcb%3d20100123214856&ehk=b44kdYM5%2fE8%2fW30ifnHZBbqTiL%2f58yYjvqKJOphO9uM%3d&risl=&pid=ImgRaw&r=0" alt="Harry Potter Film 1">
               Murid Slytherin yang sering menjadi lawan utama Harry di sekolah.
            
           <br> 8. <b>Ralph Fiennes sebagai Lord Voldemort </b> 
               <br><br><img class="image-film" src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEhI1fZC3TuOr-AiC-cy3QffUDMf5M63ddtlrQai_mc_GlD6i9A3JBJwaosel1m8OSgGE4r8ZMhzNgAaTer1kQhOGcGUzTnyppLVLoXsbckvrLA4-1v1ttr2GUnqvR4JbQk2WaClOrkZ6z2wYLGNzpZNFTbo2SmRWRNFmLSESu_JHYVKh9U4Qkg_IFRm/w640-h360-rj/RalphFiennes_Voldemort.jpg" alt="Harry Potter Film 1">
               Penyihir gelap yang menjadi musuh utama sepanjang seri, berusaha untuk menguasai dunia sihir.
            
           <br> 9. <b>Gary Oldman sebagai Sirius Black </b>
               <br><br><img class="image-film" src="https://people.com/thmb/Guvwlzl-Et4oNhuao0bghPH70KE=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():focal(749x0:751x2)/Gary-Oldman-in-Harry-Potter-122823-1-afd6f6b3caef44369dea08b76a7177b8.jpg" alt="Harry Potter Film 1">
               Paman Harry yang karismatik dan bekas tahanan Azkaban yang ternyata tidak bersalah.
            
           <br> 10. <b>Bonnie Wright sebagai Ginny Weasley</b>
               <br><br><img class="image-film" src="https://th.bing.com/th/id/OIP.WRSv-s5TYWRGolhNKAs4BQAAAA?rs=1&pid=ImgDetMain" alt="Harry Potter Film 1">
               Adik Ron dan akhirnya menjadi istri Harry Potter.
            
            <br>11. <b>Matthew Lewis sebagai Neville Longbottom</b>
               <br><br><img class="image-film" src="https://th.bing.com/th/id/R.b1f2aeb1b8aa850b36a0587f0527e862?rik=sxkr65QS5XoDzQ&riu=http%3a%2f%2fwww.wallpaperhi.com%2fthumbnails%2fdetail%2f20140119%2fharry+potter+actors+neville+longbottom+gryffindor+cast+matthew+david+lewis_www.wallpaperhi.com_97.jpg&ehk=S8b0hQR8oLzG3%2f6h4wpcJXqB44a%2fuUp0zfa9Raxc4uk%3d&risl=&pid=ImgRaw&r=0" alt="Harry Potter Film 1">
               Siswa yang awalnya canggung namun tumbuh menjadi salah satu pahlawan utama dalam cerita.
            
            <br>12. <b>Helena Bonham Carter sebagai Bellatrix Lestrange</b>  
               <br><br><img class="image-film" src="https://th.bing.com/th/id/OIP.9AV3n5fNqp_KZSfR7OOuVAHaJ4?rs=1&pid=ImgDetMain" alt="Harry Potter Film 1">
               Pengikut setia Voldemort yang berbahaya dan kejam.
            
            <br>13. <b>Jim Broadbent sebagai Horace Slughorn</b>
               <br><br><img class="image-film" src="https://th.bing.com/th/id/OIP.qXHxHZeb01c41tQ91JYItAHaJ4?rs=1&pid=ImgDetMain" alt="Harry Potter Film 1">
               Guru Ramuan yang kembali mengajar di Hogwarts dan memiliki hubungan dengan banyak penyihir terkenal.
            
           <br> 14. <b>David Thewlis sebagai Remus Lupin </b> 
               <br><br><img class="image-film" src="https://i.pinimg.com/474x/4d/5b/ec/4d5becbe9c42357c6f89a861ce5dbbfe--harry-potter-cast-lupin-harry-potter.jpg" alt="Harry Potter Film 1">
               Guru Pertahanan Terhadap Ilmu Hitam yang juga seorang werewolf, serta teman dekat orangtua Harry.
            
           <br> 15. <b>John Hurt sebagai Ollivander</b> 
               <br><br><img class="image-film" src="https://img.mensxp.com/media/content/2017/Jan/feature-image-youtube-amp-warner-bros-edited-1485593140.jpg" alt="Harry Potter Film 1">
               Pembuat tongkat sihir yang legendaris, yang memberikan tongkat pertama Harry Potter.
            
            Ini hanya beberapa aktor yang memainkan peran utama dan karakter penting dalam film Harry Potter. Banyak aktor lain juga berkontribusi dalam film ini, menciptakan dunia sihir yang kaya dan penuh karakter.

        </aside>
        </aside>

        <!-- Konten Utama -->
        <main class="content">
            <section id="beranda">
                <h2>Selamat Datang!</h2>
                <p>Jika Anda adalah penggemar sejati dari dunia sihir yang diciptakan oleh J.K. Rowling, maka Anda berada di tempat yang tepat!
                    <img src="https://www.macitynet.it/wp-content/uploads/2018/07/harry-potter-02.jpg" alt="harry Potter=ImgDetMain">
                </p>
            </section>

            <section id="film-harry-potter">
                <h2>Film Harry Potter</h2>
                <!-- Video 1 -->
                <p><b>1. Harry Potter and the Philosopher's Stone (2001)</b></p>
                <img class="image-film" src="https://www.themoviedb.org/t/p/original/bVcMIUkUH0pbk5cyPnfUPSEPgj0.jpg" alt="Harry Potter Film 1">
                <p>Film pertama dalam seri ini mengajak kita bertemu dengan Harry Potter, seorang anak yatim piatu yang menemukan dirinya sebagai penyihir. Kita diajak menyaksikan awal petualangan Harry di Hogwarts, sekolah sihir paling terkenal di dunia, serta pertemuannya dengan teman-teman setianya, Ron Weasley dan Hermione Granger.
                    <div id="video1" class="hidden">
                        <iframe class="video-film" width="600" height="455" 
                        src="https://www.youtube.com/embed/l91Km49W9qI" frameborder="0" 
                        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen>
                        </iframe>
                    </div>
                    <button id="toggle-video1" class="toggle-button" onclick="toggleContent('video1', 'toggle-video1')">Tampilkan Video</button>
                </p>

                <!-- Video 2 -->
                <p><b>2. Harry Potter and the Chamber of Secrets (2002)</b></p>
                <img class="image-film" src="https://th.bing.com/th/id/OIP.BoAGip41BazSoCE7mHu1IwAAAA?rs=1&pid=ImgDetMain" alt="Harry Potter Film 2">
                <p>Kisah berlanjut dengan rahasia yang tersembunyi di dalam Hogwarts. Harry harus menghadapi kekuatan jahat yang mengancam nyawa siswa-siswa di sekolah, dan misteri di balik Kamar Rahasia yang legendaris.
                </p>
                <div id="video2" class="hidden">
                    <iframe class="video-film" width="600" height="455" 
                    src="https://www.youtube.com/embed/nE11U5iBnH0" frameborder="0" 
                    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen>
                    </iframe>
                </div>
                <button id="toggle-video2" class="toggle-button" onclick="toggleContent('video2', 'toggle-video2')">Tampilkan Video</button>
                </p>

                <p><b>3.Harry Potter and the Prisoner of Azkaban (2004) </b></p>
            </p><br><img src="https://image.tmdb.org/t/p/original/sCrAJB4mwiUu9ymq0aRFWY6DcM1.jpg" alt="Harry Potter and the Prisoner of Azkaban (2004)">
                <p>Petualangan semakin menegangkan ketika Sirius Black, seorang narapidana berbahaya, kabur dari penjara Azkaban dan tampaknya sedang memburu Harry. Namun, misteri di balik hubungan Sirius dengan keluarga Harry segera terungkap. 
                    <div id="video3" class="hidden">
                        <iframe class="video-film" width="600" height="455" src="https://www.youtube.com/embed/VwErvYgoH70" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
                    </div>
                    <button id="toggle-video3" class="toggle-button" onclick="toggleContent('video3', 'toggle-video3')">Tampilkan Video</button>
                </p>
                
               <br><b>4. Harry Potter and the Goblet of Fire (2005)</b>
               </p><br><img src="https://th.bing.com/th/id/OIP.njBGrOMqIjvp7O3lHjMyKAHaLH?rs=1&pid=ImgDetMain" alt="Harry Potter and the Goblet of Fire (2005)">
               <br>Dalam film ini, Harry secara tak terduga terpilih menjadi peserta dalam Turnamen Triwizard, sebuah kompetisi sihir berbahaya. Namun, di balik turnamen ini tersembunyi rencana kelam yang melibatkan kembalinya Lord Voldemort.
               <br><div id="video4" class="hidden">
                <iframe class="video-film" width="600" height="455" src="https://www.youtube.com/embed/80kuiBq95So" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
                </div>
                <button id="toggle-video4" class="toggle-button" onclick="toggleContent('video4', 'toggle-video4')">Tampilkan Video</button>
                </p>
                <p><b>5. Harry Potter and the Order of the Phoenix (2007)</b>
                </p><br><img src="https://th.bing.com/th/id/OIP.AuR3pPnZkPkBm8a8tdcoaAHaLH?rs=1&pid=ImgDetMain" alt="Harry Potter and the Order of the Phoenix (2007)">
                <br>Harry dan teman-temannya mendirikan Dumbledore's Army untuk melawan ancaman Voldemort yang semakin nyata. Di sisi lain, pengaruh Kementerian Sihir yang meragukan kembalinya Voldemort mulai memperketat kontrol mereka atas Hogwarts.
                <br>
                <div id="video5" class="hidden">
                    <iframe class="video-film" width="600" height="455" src="https://www.youtube.com/embed/LLAaW1EgyY8" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
                </div>
                <button id="toggle-video5" class="toggle-button" onclick="toggleContent('video5', 'toggle-video5')">Tampilkan Video</button>
                </p>
                <br> <b>6. Harry Potter and the Half-Blood Prince (2009)</b>
                </p><br><img src="https://th.bing.com/th/id/OIP.1VhaWRoYITizEkrpMc585QHaLH?rs=1&pid=ImgDetMain" alt="Harry Potter and the Half-Blood Prince (2009)">
                <br>Harry menemukan buku ramuan misterius yang pernah dimiliki oleh seorang Pangeran Berdarah Campuran. Saat kebenaran tentang masa lalu Voldemort mulai terkuak, Hogwarts menjadi lebih berbahaya dari sebelumnya.

                <br><b>7. Harry Potter and the Deathly Hallows - Part 1 & 2 (2010-2011)</b>
                </p><br><img src="https://static.rogerebert.com/uploads/movie/movie_poster/harry-potter-and-the-deathly-hallows-part-1-2010/large_6nHrNTF3qOY19m07paTI8idEaFU.jpg" alt="Harry Potter and the Deathly Hallows - Part 1 & 2 (2010-2011)">
                <img src="https://img.yts.mx/assets/images/movies/Harry_Potter_and_the_Deathly_Hallows_Part_2_2011/large-cover.jpg" alt="Harry Potter and the Deathly Hallows - Part 1 & 2 (2010-2011)">
                <br>Pertarungan terakhir antara Harry dan Voldemort semakin dekat. Di bagi dalam 2 part film, Harry, Ron, dan Hermione berusaha menemukan Horcrux, objek-objek yang mengandung bagian jiwa Voldemort, untuk menghancurkannya. Pertarungan epik di Hogwarts pun menjadi puncak dari seluruh kisah.
            </p>
                    </p>
                </section>
                <section id="karakter-utama">
                    <h2>Karakter Utama</h2>
                    <p><p>Sebelum kita masuk ke dalam dunia sihir Hogwarts yang penuh dengan petualangan seru, yuk kenalan dulu sama para karakter utama yang bikin cerita Harry Potter jadi tak terlupakan! 
                        <br>Dari penyihir muda dengan bekas luka di dahinya, sampai guru galak dengan rahasia besar, mereka semua punya keunikan masing-masing yang bikin kita terus kepincut sama dunia sihir ini. Siap? Pegang erat tongkat sihirmu, karena kita akan menjelajah lebih jauh dan mengenal para pahlawan (dan musuh!) di balik kisah epik ini!
                        <br>Baiklah mari simak beberapa karakter yang memiliki peran utama pada film ini!.
                        </p>1. <b>Harry Potter</b> - Si bocah penyihir dengan bekas luka petir di dahinya ini mungkin awalnya terlihat biasa saja, tapi jangan salah! Harry adalah kombinasi sempurna antara keberanian dan kebaikan hati. Meski hidupnya penuh tantangan, mulai dari masa kecil yang suram di rumah Dursley sampai harus menghadapi musuh bebuyutan yang super jahat, Harry selalu punya tekad baja dan kesetiaan tanpa batas untuk teman-temannya. Bisa dibilang, dia adalah ikon “anak terpilih” yang benar-benar berani.
                        </p>2. <b>Hermione Granger</b> - Kalau otak adalah senjata utama, maka Hermione pasti sudah jadi pahlawan dunia sejak dulu. Gadis ini nggak cuma pintar, tapi super logis dan penuh rasa ingin tahu. Setiap masalah yang muncul, Hermione selalu punya jawaban di ujung lidahnya. Kalau nggak ada dia, rasanya Harry dan Ron mungkin sudah terjebak dalam masalah yang lebih rumit! Dia adalah simbol kecerdasan yang bikin kagum dan sahabat yang selalu bisa diandalkan.
                        </p>3. <b>Ron Weasley</b> - Si merah ini memang kocak dan kadang canggung, tapi jangan remehkan! Di balik candaan dan rasa takut terhadap laba-laba, Ron punya hati emas dan setia banget sama teman-temannya. Di antara trio ini, Ron sering jadi penghibur, tapi saat situasi mendesak, dia tahu kapan harus serius dan siap menghadapi bahaya. Plus, siapa yang bisa melupakan keberaniannya saat bermain catur sihir raksasa?
                        </p>4. <b>Albus Dumbledore</b> - Kepala sekolah Hogwarts yang penuh misteri ini nggak cuma bijaksana, tapi juga selalu punya satu atau dua trik di balik jubahnya. Dengan kumis dan jenggot panjangnya, Dumbledore bagaikan mentor super yang punya jawaban untuk semua masalah—walau kadang menyampaikannya dalam teka-teki yang bikin mikir keras. Dia adalah simbol kebijaksanaan dengan sentuhan humor dan kehangatan.
                        </p>5. <b>Severus Snape</b>- Pada awalnya, Snape tampak seperti guru paling galak dan penuh kebencian. Tapi siapa sangka, karakter ini memiliki cerita yang lebih dalam dari sekadar tatapan tajam dan jubah hitam. Cinta tersembunyinya untuk Lily Potter dan pengorbanannya yang luar biasa membuat kita berubah pandangan. Dari seorang yang tampak jahat, Snape justru adalah salah satu karakter paling kompleks dan tragis di dunia Harry Potter.
                        </p>6. <b>Draco Malfoy</b> - Si musuh bebuyutan Harry ini memang sok dan penuh kesombongan, tapi di balik wajah angkuhnya, Draco adalah contoh remaja yang terjebak dalam bayang-bayang keluarganya. Dia sering bingung antara keinginan untuk terlihat kuat dan tekanan yang datang dari lingkungannya. Pada akhirnya, Draco adalah bukti kalau bahkan orang yang tampak jahat sekalipun bisa punya sisi manusiawi yang rapuh.
                        </p>7. <b>Lord Voldemort</b>- Nah, kalau yang satu ini, nggak ada yang lebih menyeramkan dari penyihir yang namanya pun bikin bulu kuduk merinding. Voldemort bukan cuma licik, tapi juga ambisius dengan satu tujuan: kekuasaan tanpa batas. Dia adalah musuh utama yang punya dendam mendalam terhadap Harry, dan setiap kemunculannya di layar selalu membuat kita tegang.
                        <br>Setiap karakter di film Harry Potter punya keunikan dan cerita tersendiri yang bikin kita jatuh cinta, dari yang paling ceria sampai yang paling gelap!
                        <br>
                    </p>
                </section>

                <section id="trivia-fakta-menarik">
                    <h2>Trivia & Fakta Menarik</h2>
                    <p>Nah! Berikut beberapa Trivia & Fakta Menarik tentang film Harry Potter yang bakal bikin kamu makin cinta sama dunia sihir ini:
                        <p>1. Bekas Luka Harry 
                            Tahukah kamu? Bekas luka berbentuk petir di dahi Harry Potter dibuat lebih dari 5,800 kaliselama produksi film! Ya, Daniel Radcliffe harus dipakaikan bekas luka itu setiap kali syuting – betul-betul kerja keras tim makeup, ya!
                         
                        </p>2. Kacamata Harry  
                            Daniel Radcliffe menggunakan 160 pasang kacamata selama pembuatan film! Kacamatanya nggak cuma aksesori, tetapi jadi ikon gaya Harry yang sangat khas.
                         
                         </p>3. Hermione Hampir Punya Gigi Palsu!
                            Dalam buku, Hermione digambarkan memiliki gigi depan yang sedikit lebih besar. Awalnya, Emma Watson akan memakai gigi palsu saat syuting, tapi karena sulit untuk berbicara, akhirnya rencana itu dibatalkan. Syukurlah, kan?
                         
                        </p>4. Ruangan yang Bergerak  
                            Tangga di Hogwarts benar-benar bisa bergerak, lho! Tim efek visual menciptakan tangga yang bergerak di berbagai film, menambah sentuhan magis di kastil itu. Rasanya kayak beneran ada di Hogwarts!
                         
                        </p>5. Nagini Terinspirasi dari Ular Asli  
                            Ingat Nagini, ular raksasa Voldemort? Ternyata pergerakannya terinspirasi dari ular piton asli! Para desainer visual benar-benar mempelajari gerakan ular untuk memastikan Nagini tampak nyata dan menyeramkan.
                         
                        </p>6. Emma Watson Nyaris Keluar!  
                            Emma Watson hampir meninggalkan perannya sebagai Hermione setelah film keempat karena ingin fokus pada pendidikan. Untungnya, dia memutuskan tetap lanjut, dan kita bisa terus melihat Hermione yang cerdas di layar.
            
                        </p>7. Dumbledore yang Menyanyi? 
                            Michael Gambon, pemeran Dumbledore di sebagian besar film, kadang iseng menyanyi dan bercanda di set. Dia sangat berbeda dari karakter Dumbledore yang serius, tapi itu yang bikin suasana syuting jadi seru!
                         
                        </p>8. Syuting di Kastil Asli  
                            Hogwarts yang megah tidak semuanya dibangun di studio, lho. Beberapa adegan diambil di kastil-kastil dan katedral di Inggris, seperti Alnwick Castle dan Gloucester Cathedral. Kalau kamu main ke sana, rasanya seperti masuk ke dunia sihir beneran!
                        <br>Fakta-fakta ini bikin Harry Potter jadi makin spesial, kan? Kira-kira fakta mana yang paling bikin kamu takjub?
                    </p>
                </section>
                <section id="akhir-kata">
                    <h2>Akhir Kata</h2>
                    <p>Dunia Harry Potter penuh dengan petualangan, misteri, dan keajaiban yang tidak pernah berhenti memukau para penggemarnya. Melalui situs ini, kami berharap Anda dapat mengeksplorasi lebih dalam lagi dunia sihir yang begitu dicintai oleh banyak orang di seluruh dunia. Terima kasih telah berkunjung, dan mischief managed!</p>
                </section>
            </main>

            <!-- Sidebar Kanan -->
                <aside class="sidebar-right">
                        <h3>Beberapa Link Informasi lainnya tentang dunia sihir Film Harry Potter</h3>
                        <p>
                            <a href="https://harrypotter.fandom.com/wiki/List_of_Harry_Potter_cast_members" 
                               target="_blank" style="color: white; font-weight: bold;">
                               Informasi Daftar Aktor Film Harry Potter
                            </a>
                        </p>
                        <p>
                            <a href="https://m.antaranews.com/amp/berita/3619542/daniel-radcliffe-tak-ingin-ambil-bagian-di-seri-terbaru-harry-potter" 
                               target="_blank" style="color: white; font-weight: bold;">
                               Daniel Radcliffe tak ingin ambil bagian di seri terbaru "Harry Potter"
                            </a>
                        </p>
                        <p>
                            <a href="https://www.antaranews.com/berita/3222405/warner-bros-ingin-buat-lebih-banyak-film-harry-potter" 
                               target="_blank" style="color: white; font-weight: bold;">
                               Warner Bros ingin buat lebih banyak film "Harry Potter"
                            </a>
                        </p>
                        <p>
                            <a href="https://deadline.com/2024/09/harry-potter-tv-series-max-release-date-cast-1235323284/" 
                               target="_blank" style="color: white; font-weight: bold;">
                               Serial TV 'Harry Potter' Akan Tayang di HBO Tahun 2026
                            </a>
                        </p>
                        <p>
                            <a href="https://buku.kompas.com/read/4099/4-fakta-menarik-di-balik-suksesnya-film-harry-potter-karya-jk-rowling" 
                               target="_blank" style="color: white; font-weight: bold;">
                               4 Fakta Menarik di Balik Suksesnya Film Harry Potter Karya J.K Rowling
                            </a>
                        </p>
                        <p>
                            <a href="https://screenrant.com/harry-potter-cursed-child-movie-will-it-happen-cast-comments/" 
                               target="_blank" style="color: white; font-weight: bold;">
                               Film Harry Potter & The Cursed Child: Akankah Terjadi? Apa Kata Para Pemeran & Semua yang Kita Ketahui
                            </a>
                        </p>
                        <p>
                            <a href="https://mediaindonesia.com/hiburan/457874/harry-potter-20th-anniversary-return-to-hogwarts-tayang-di-hbo-go-pada-1-januari"
                               target="_blank" style="color: white; font-weight: bold;">
                               Harry Potter 20th Anniversary: Return to Hogwarts Tayang di HBO Go Pada 1 Januari
                            </a>
                        </p>
                        <p>
                            <a href="https://www.kompas.com/cekfakta/read/2022/06/30/191900082/kontroversi-di-balik-harry-potter-dan-bantahannya-"
                               target="_blank" style="color: white; font-weight: bold;">
                               Kontroversi di Balik Harry Potter dan Bantahannya
                            </p>
                            <p>
                                <a href="https://news.detik.com/berita/d-5227838/tentang-nagini-ular-di-harry-potter-yang-mitosnya-dari-jawa"
                                   target="_blank" style="color: white; font-weight: bold;">
                                   Tentang Nagini, Ular di Harry Potter yang Mitosnya dari Jawa
                                </a>
                            </p>
                            <p>
                                <a href="https://entertainment.kompas.com/read/2022/10/05/175755166/kata-kata-bijak-film-harry-potter"
                                   target="_blank" style="color: white; font-weight: bold;">
                                   Kata-kata Bijak Film Harry Potter
                                </a>
                            </p>
                    </aside>
                    
                           
            </aside>
            
        <!-- Footer -->
        <footer>
            &copy; 2024 Informasi Harry Potter. Semua Hak Dilindungi.
        </footer>
        
        <script>
            function toggleContent(contentId, buttonId) {
                const content = document.getElementById(contentId);
                const button = document.getElementById(buttonId);

                if (!content || !button) {
                    console.error('Elemen tidak ditemukan:', contentId, buttonId);
                    return;
                }

                if (content.classList.contains('hidden')) {
                    content.classList.remove('hidden');
                    button.textContent = 'Sembunyikan';
                } else {
                    content.classList.add('hidden');
                    button.textContent = 'Tampilkan';
                }
            }
            window.addEventListener("load", function () {
                document.body.classList.add("loaded");

                setTimeout(function () {
                    document.getElementById("splitter").style.display = "none";
                }, 1000);
            });
            
        </script>
    </body>
    </html>
