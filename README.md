# calcudaus.github.io
<!DOCTYPE html>
<html lang="id">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Membuat Website Sederhana</title>
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <!-- Ini Header Dari Sebuah Website -->
    <header>
      <div class="jumbotron">
        <h1>Medan</h1>
        <p>
          Medan adalah ibu kota provinsi Sumatra Utara, Indonesia. Kota ini
          merupakan kota terbesar ketiga di Indonesia setelah DKI Jakarta dan
          Surabaya serta kota terbesar di luar pulau Jawa, sekaligus terbesar di
          Pulau Sumatra.
        </p>
      </div>

      <nav>
        <ul>
          <li><a href="#sejarah">Sejarah</a></li>
          <li><a href="#geografis">Geografis</a></li>
          <li><a href="#wisata">Wisata</a></li>
        </ul>
      </nav>
    </header>

    <!-- Konten Website  -->
    <main>
      <div id="content">
        <article id="sejarah" class="card">
          <h2>Sejarah</h2>
          <img
            src="Image/KotaMedan.jpeg"
            alt="Sejarah"
            class="featured-image"
          />
          <p>
            Sejarah Medan berawal dari sebuah kampung yang didirikan oleh Guru
            Patimpus di pertemuan Sungai Deli dan Sungai Babura. Hari jadi Kota
            Medan ditetapkan pada 1 Juli 1590.
          </p>
          <p>
            Selanjutnya pada tahun 1632, Medan dijadikan pusat pemerintahan
            Kesultanan Deli, sebuah kerajaan Melayu.
          </p>
        </article>

        <article id="geografis" class="card">
          <h2>Geografis</h2>
          <img
            src="Image/Geografis.jpeg"
            alt="Geografis"
            class="featured-image"
          />
          <p>
            Kota Medan adalah Ibukota dari Provinsi Sumatra Utara yang berada
            pada Koordinat: 3°30'- 3°43'LU 98°35'-98°44'BT dengan luas wilayah
            sekitar 265,10 km², penduduknya mencapai 2.036.018 jiwa .
          </p>
        </article>

        <article id="wisata" class="card">
          <h2>Wisata</h2>
          <img src="Image/Wisata.jpeg" alt="Wisata" class="featured-image" />
          <p>
            Medan merupakan salah satu wilayah yang sudah banyak di lirik oleh
            para wisatawan asing maupun lokal.
          </p>
          <section>
            <h3>Danau Toba</h3>
            <img
              src="Image/DanauToba.jpg"
              alt="DanauToba"
              class="featured-image"
            />
            <p>
              Danau Toba Merupakan sebuah danau terbesar seAsia tenggara yang
              terbentuk karena letusan gunung vulkanik berabad abad Lalu
            </p>
          </section>

          <section>
            <h3>Sipiso - piso</h3>
            <img
              src="Image/SipisoPiso.jpeg"
              alt="SipisoPiso"
              class="featured-image"
            />
            <p>
              Sipiso Piso Merupakan sebuah air terjun yang terdapat di kota
              medan yang sangat indah <br />
              Tapi sayang nya untuk menuju ke titik pusat air terjun anda perlu
              menuruni anak tangga yang sangat amat banyak hampir 1000 anak
              tangga yang anda turuni untuk menikmati keindahan air terjun
              sipiso piso
            </p>
          </section>
        </article>
      </div>

      <aside class="profile card">
        <article class="profile">
          <header>
            <h2>Kota Medan</h2>
            <p id="kota-metropolitan">Kota Metropolitan</p>
            <figure>
              <img src="image/kotamedanlambang.jpeg" alt="lambangKotaMedan" />
              <figcaption>Lambang</figcaption>
            </figure>
          </header>
          <section>
            <h3>Informasi Lainnya</h3>
            <table>
              <tr>
                <th>Negara</th>
                <td>Indonesia</td>
              </tr>
              <tr>
                <th>Hari Jadi</th>
                <td>1 Juli 1950</td>
              </tr>
              <tr>
                <th>Luas Total</th>
                <td>265,1 km²</td>
              </tr>
              <tr>
                <th>Bahasa Daerah</th>
                <td>Batak</td>
              </tr>

              <tr>
                <th>KodeTelepon</th>
                <td>+061</td>
              </tr>
            </table>
          </section>
        </article>
      </aside>
    </main>

    <!-- Footer / Catatan Kaki -->
    <footer>
      <p>Belajar Membuat&nbsp; Wesite &copy;2022</p>
    </footer>
  </body>
</html>
