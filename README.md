# Guide Arlink Web Deploy 

## Apa itu ARlink ???
ARlink merupakan gabungan kekuatan penyimpanan yang terdesentralisasi dengan alur kerja penerapan yang familier, sehingga memudahkan Anda menghadirkan aplikasi ke permaweb.

## Bagaimana cara kita dapat berinteraksi diplatform Arlink ???
Simple dan mudah sekali untuk kita dapat berinteraksi diplatform Arlink, kita dapat melakukan deployment WEB menggunakan platform ini, sebagai bentuk interaksi dan ujicoba dari platform Arlink Ini. saya akan berbagai step by step dari awal hingga akhir untuk berinteraksi.

## Guide Step By Step 

## 🟢 Step 1 (Membuat web sederhana)
Pada tahap awal ini tugas kita adalah melakukan pembuatan WEB, kreativitas tidak menjadi hal utama pada step ini, namun tidak semua orang dapat memahami dengan mudah tentang bagaimana cara dasar membuat sebuah web yang sederhana, mari kita wujudkan hal tersebut

Persiapan Tolls :
- VS code
- Github Account
- Notepad 
- Domain ARNS 

Jika Tolls sudah siap, di step ini kita akan melakukan penulisan code untuk mewujudkan tampilan sebuah WEB, disini kalian bisa berkreasi sebebas mungkin mau menggunakan HTML, CSS, JS ataupun yang lainnya, kalian juga bisa memanfaatkan ChatGPT atau bisa menggunakan code akan saya lampirkan di bawah.

Code HTML (Format penamaan FILE index.html) :
```
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portofolio Masdimas</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Portofolio Masdimas</h1>
        <nav>
            <a href="#about">Tentang</a>
            <a href="#projects">Proyek</a>
            <a href="#contact">Kontak</a>
        </nav>
    </header>

    <div class="container">
        <section id="about" class="section">
            <h2>Tentang Saya</h2>
            <div class="card">
                <p>Halo! Nama saya Masdimas. Saya adalah seorang penggemar blockchain dan teknologi web3. Saya telah berpartisipasi dalam berbagai proyek testnet, menjalankan validator node, dan membangun komunitas. Di waktu luang, saya juga suka traveling dan mencoba pengalaman baru.</p>
            </div>
        </section>

        <section id="projects" class="section">
            <h2>Proyek</h2>
            <div class="card">
                <h3>Proyek Blockchain</h3>
                <p>Saya telah bekerja di beberapa proyek seperti PWR Chain, Rainbow Protocol, dan banyak lainnya. Saya memiliki pengalaman dalam pengaturan node validator dan pengembangan komunitas.</p>
            </div>
            <div class="card">
                <h3>Artikel dan Tutorial</h3>
                <p>Saya membuat tutorial untuk proyek DeFi dan testnet, seperti cara menggunakan dompet blockchain atau membuat token di jaringan tertentu.</p>
            </div>
        </section>

        <section id="contact" class="section">
            <h2>Kontak</h2>
            <div class="card">
                <p>Hubungi saya melalui email: <a href="masdimas@example.com">masdimas@example.com</a></p>
                <p>Ikuti saya di media sosial: <a href="https://twitter.com/masdimas">Twitter</a></p>
            </div>
        </section>
    </div>

    <footer>
        <p>&copy; 2025 Masdimas. Semua Hak Dilindungi.</p>
    </footer>
</body>
</html>
```

Code CSS (Format penamaan FILE style.css) :
```
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f9;
    color: #333;
}

header {
    background-color: #007bff;
    color: white;
    padding: 20px 0;
    text-align: center;
}

header h1 {
    margin: 0;
    font-size: 2.5em;
}

nav {
    margin-top: 10px;
}

nav a {
    color: white;
    margin: 0 15px;
    text-decoration: none;
    font-weight: bold;
}

.container {
    width: 90%;
    max-width: 1200px;
    margin: 20px auto;
}

.section {
    margin-bottom: 40px;
}

.section h2 {
    color: #007bff;
    border-bottom: 2px solid #007bff;
    display: inline-block;
    margin-bottom: 20px;
}

.card {
    background: white;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
    padding: 20px;
    margin-bottom: 20px;
    border-radius: 5px;
}

footer {
    background-color: #007bff;
    color: white;
    text-align: center;
    padding: 10px 0;
    position: fixed;
    bottom: 0;
    width: 100%;
}
```
Step selanjutnya kalian bisa mengedit code yang saya lampirkan sesuai minat dan keinginan, jika dirasa sudah cukup kalian bisa save sesuai dengan format penamaan file.
Buka akun github dan buatlah repository baru sesuai nama projek yang kalian inginkan, kemudian upload file yang sudah disimpah sebelumnya ke-dalam repository, save and commit.

## 🟢Step 2 (Deployment di Arlink)

1. Di step 3 kalian bisa langsung membuka : https://arlink.arweave.net
2. Hubungkan dengan wallet arwave kalian
3. klik deploy your first app kemudian pilih github dan konek github
4. Pilih Repository yang sudah dibuat
5. Jika sudah akan menuju ke halaman Create new deployment, selanjutnya seusaikan dan ganti seperti dibawa
   - Install Command = npm --version
   - Build Command   = npm -- version
   - Sub Dir = ./
   - Out Dir = .
6. Klik next kemudian aktifkan ArNS domain, kemudian masukan process id dari domain yang sudah kalian buat
7. Klik Deploy dan tunggu proses berjalan hingga selesai, tanda selesai akan memunculkan keterangan build completed
8. Done

## Join 
https://arlink.gitbook.io/arlink-docs

https://x.com/arlinklabs

https://discord.gg/uTAEwbKF




