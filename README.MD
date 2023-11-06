# Jaringan Nirkabel

## Pengertian

Jaringan tanpa kabel adalah suatu jaringan area tanpa kabel dimana media transmisinya

## Standar Nirkabel :

#### `WAN` (Wide Area Network) IEEE 802.20

```bash
Contoh : jaringan antar kota / negara
Jarak : 100km - 1000 km
```

#### `MAN` (Metropolitan Area Network) IEEE 802.16

```bash
Contoh : Jaringan antar kota
Jarak : < 10KM
```

#### `LAN` (Local Area Network) IEEE 802.11

```bash
Contoh : Jaringan antar komputer
Jarak : 10M - 1Km
```

#### `PAN` (Personal Area Network) IEEE 802.15

```bash
Contoh : Bluetooth
Jarak : < 10m
```

## kelebihan :

- Mobilitas tinggi
- Kemudahan dan kecepatan instalasi
- Fleksibel Jangkauan luas
- Biaya pemeliharannya murah (hanya mencakup stasiun bukan seperti pada jaringan kabel yang mencakup keseluruhan kabel).
- infrastrukturnya berdimensi kecil.
- mudah dikembangkan.
- mudah & murah untuk direlokasi dan mendukung portabilitas

## Kelemahan :

- Keamanan data (Kerahasian) kurang terjamin.
- Transmit data kecil (Kapasitas jaringan terbatas)
- Mudah terjadi gangguan antara pengguna yang lain ( Interferensi Gelombang )
- Intermittence ( sinyal putus-putus )
- Mempunyai latency yang cukup besar dibandingkan dengan media transmisi kabel (Delay yang besar)

# Standar Jaringan Nirkabel IEEE

## `IEEE 802.11 `

`IEEE 802.11` adalah serangkaian standar komunikasi nirkabel yang digunakan untuk jaringan lokal nirkabel (Wireless Local Area Network atau WLAN).

### Kelebihan IEEE 802.11:

- `Mobilitas`: Memungkinkan perangkat untuk bergerak secara bebas tanpa harus terhubung ke kabel, sehingga sangat cocok untuk perangkat seluler seperti laptop, ponsel, dan tablet.

- `Fleksibilita`s: Standar ini mendukung berbagai jenis aplikasi, termasuk transfer data, telepon VoIP, dan streaming video.

- `Mudah diimplementasikan`: Jaringan IEEE 802.11 relatif mudah diimplementasikan, memungkinkan penggunaan di berbagai lingkungan.

- `Berkembang`: Berbagai versi IEEE 802.11 telah diperkenalkan seiring waktu untuk meningkatkan kecepatan dan keamanan, seperti 802.11n, 802.11ac, dan 802.11ax.

### Kekurangan IEEE 802.11:

- `Rentan terhadap gangguan`: Jaringan nirkabel rentan terhadap gangguan dari perangkat lain dan dinding atau objek dalam lingkungan.

- `Keamanan`: Keamanan jaringan nirkabel dapat menjadi masalah jika tidak diatur dengan benar. Versi awal IEEE 802.11 (seperti 802.11b) rentan terhadap serangan keamanan.

- `Kapasitas terbatas`: Jaringan nirkabel berbagi bandwidth, yang berarti semakin banyak perangkat yang terhubung, semakin rendah kecepatan yang tersedia untuk setiap perangkat.

- `Jarak terbatas`: Jarak operasi perangkat IEEE 802.11 terbatas, dan koneksi dapat melemah dengan jarak yang jauh dari akses poin (router).

### Tantangan dalam menggunakan media transmisi dalam standar IEEE 802.11 meliputi:

- `Keamanan`: Menjaga jaringan nirkabel aman dari serangan atau akses yang tidak sah adalah tantangan utama, dan memerlukan pengaturan keamanan yang kuat.

- `Interferensi dan Kapasitas`: Meningkatkan kinerja jaringan dalam lingkungan yang penuh dengan perangkat nirkabel dan interferensi adalah tantangan, terutama di lingkungan padat.

- `Skalabilitas`: Mengelola pertumbuhan jumlah perangkat yang terhubung ke jaringan nirkabel dapat menjadi tantangan.

- `Jarak dan Cakupan`: Memastikan cakupan yang memadai dan kualitas sinyal dalam jaringan nirkabel di berbagai area adalah masalah yang perlu diatasi.

### Contoh perangkat dan teknologi yang menggunakan IEEE 802.11 termasuk:

- Laptop dan komputer pribadi dengan kartu nirkabel (Wi-Fi).
- Smartphone dan tablet dengan kemampuan Wi-Fi.
- Router nirkabel dan akses poin.
- Ponsel VoIP (Voice over Internet Protocol).
- Perangkat Internet of Things (IoT) seperti kamera keamanan nirkabel dan sensor suhu.
- Perangkat-perangkat yang digunakan dalam lingkungan bisnis seperti perusahaan, kampus, bandara, dan pusat perbelanjaan.

---

## IEEE 802.15

Standar IEEE 802.15 adalah serangkaian standar yang mengatur jaringan nirkabel jarak pendek, khususnya untuk perangkat berbasis sensor dan perangkat Internet of Things (IoT).

ada 3 macam turunan dari standar 802.15

- `IEEE 802.15.1` (Bluetooth): Ini adalah subkelompok yang mendefinisikan protokol komunikasi nirkabel `Bluetooth`. Bluetooth digunakan untuk menghubungkan perangkat seperti ponsel, headset, speaker, dan perangkat lain dalam jarak pendek.

- `IEEE 802.15.4`: Ini adalah subkelompok yang fokus pada `perangkat IoT` dan sensor nirkabel. Standar ini mendefinisikan protokol komunikasi dan lapisan fisik yang digunakan dalam jaringan nirkabel sensor dan jarak pendek.

- `IEEE 802.15.6`: Subkelompok ini fokus pada komunikasi tubuh manusia yang mendukung aplikasi medis dan kesehatan. Ini mencakup `sensor nirkabel` yang digunakan dalam perawatan kesehatan dan pemantauan medis.

### Kelebihan :

- `Konsumsi Energi Rendah`: Protokol dalam IEEE 802.15.4 dirancang untuk menghemat daya baterai pada perangkat sensor dan IoT, sehingga sangat cocok untuk perangkat bertenaga baterai yang harus beroperasi dalam waktu yang lama.

- `Jarak Pendek`: Standar ini cocok untuk komunikasi dalam jarak pendek, yang berguna untuk aplikasi seperti sensor jarak dekat dan perangkat IoT yang berkomunikasi dalam area terbatas.
  Skalabilitas: Protokol IEEE 802.15.4 mendukung jaringan yang dapat diperluas dengan mudah ketika Anda menambahkan lebih banyak perangkat ke dalamnya.

- `Biaya Rendah`: Perangkat keras yang sesuai dengan standar ini umumnya relatif murah, menjadikannya pilihan yang ekonomis untuk implementasi IoT.

### Kelemahan :

- `Jangkauan Terbatas`: Standar ini terutama cocok untuk jaringan jarak pendek, sehingga tidak cocok untuk aplikasi yang memerlukan jangkauan yang lebih luas.

- `Kecepatan Terbatas`: Kecepatan transfer data dalam standar ini terbatas, sehingga tidak cocok untuk aplikasi yang memerlukan throughput tinggi.

- `Rentan terhadap Interferensi`: Jaringan jarak pendek seperti yang digunakan dalam IEEE 802.15.4 dapat rentan terhadap interferensi dari perangkat lain dalam lingkungan yang sibuk.

### Tantangan dalam menggunakan media transmisi dalam standar IEEE 802.15 meliputi:

- `Manajemen Energi`: Untuk perangkat sensor dan IoT dengan daya baterai terbatas, manajemen daya yang efisien adalah tantangan besar.

- `Jaringan yang Berkembang`: Memastikan jaringan yang dapat diperluas dengan mudah ketika perangkat baru ditambahkan dan lebih banyak perangkat terhubung adalah tantangan yang harus diatasi.

- `Interferensi dan Koordinasi`: Dalam lingkungan yang padat, mengelola interferensi dan mengkoordinasikan komunikasi antar perangkat menjadi penting untuk menjaga kinerja jaringan yang baik.

---

## IEEE 802.16

Standar IEEE 802.16, yang juga dikenal sebagai WiMAX (Worldwide Interoperability for Microwave Access), adalah serangkaian standar yang mengatur teknologi komunikasi nirkabel berkecepatan tinggi yang digunakan dalam jaringan akses tetap dan bergerak.

### Kelebihan (WiMAX):

- `Jarak Jauh`: WiMAX dapat menyediakan jangkauan yang lebih jauh daripada teknologi Wi-Fi, sehingga sangat berguna untuk daerah yang tidak terjangkau oleh infrastruktur kabel.

- `Kecepatan Tinggi`: Standar WiMAX mendukung kecepatan data yang tinggi, yang menjadikannya pilihan yang baik untuk layanan berkecepatan tinggi seperti broadband nirkabel.

- `Mobilitas`: Versi WiMAX yang lebih baru, seperti IEEE 802.16e dan 802.16m, mendukung mobilitas, yang memungkinkan pengguna untuk bergerak saat tetap terhubung ke jaringan.

- `Efisiensi Spektrum`: WiMAX dirancang untuk memanfaatkan spektrum radio yang tersedia secara lebih efisien daripada teknologi seperti Wi-Fi.

### Kelemahan (WiMAX):

- `Biaya Infrastruktur`: Implementasi infrastruktur WiMAX memerlukan investasi yang signifikan dalam peralatan dan spektrum radio, sehingga biayanya dapat tinggi.

- `Spektrum Terbatas`: WiMAX bergantung pada spektrum radio yang terbatas, yang dapat menyebabkan masalah interferensi jika digunakan dalam lingkungan yang padat.

- `Penyebaran Terbatas`: WiMAX tidak sepopuler Wi-Fi dan tidak tersedia secara luas di semua lokasi, sehingga konektivitas dapat terbatas pada daerah-daerah tertentu.

- `Kelemahan dalam Mobilitas`: Meskipun WiMAX mendukung mobilitas, ini tidak secepat teknologi seperti 4G atau 5G dalam konteks perangkat bergerak.

### Tantangan dalam menggunakan media transmisi WiMAX meliputi:

- `Manajemen Spektrum`: Dalam lingkungan yang padat, manajemen spektrum dan koordinasi spektrum menjadi kunci untuk menghindari interferensi dan memastikan kinerja yang baik.

- `Biaya Implementasi`: Biaya awal dalam membangun infrastruktur WiMAX, terutama dalam frekuensi lisensi, dapat menjadi tantangan bagi penyedia layanan.

- `Kompetisi dengan Teknologi Lain`: WiMAX bersaing dengan teknologi seluler seperti 4G dan 5G, yang menawarkan mobilitas yang lebih baik dan kecepatan yang lebih tinggi dalam banyak kasus.

---

## IEEE 802.20

Standar IEEE 802.20 adalah standar yang ditujukan untuk jaringan nirkabel bergerak berkecepatan tinggi, yang awalnya disebut sebagai "Mobile Broadband Wireless Access" (MBWA).

`Tujuan :` IEEE 802.20 dirancang untuk mengatasi kebutuhan akan akses nirkabel bergerak berkecepatan tinggi yang lebih efisien dan handal dibandingkan dengan teknologi seluler saat itu.

`Akses Bergerak :` Standar ini ditujukan untuk memberikan konektivitas bergerak dalam mobil, kereta api, dan pada perangkat bergerak lainnya dengan kecepatan tinggi dan keandalan.

`Teknologi OFDMA :` Standar ini mengadopsi teknologi akses berbagi spektrum Orthogonal Frequency Division Multiple Access (OFDMA) untuk mengatasi masalah interferensi dan meningkatkan efisiensi spektrum.

### Kelebihan:

- `Kecepatan Tinggi :` Standar ini dimaksudkan untuk memberikan kecepatan data yang tinggi, yang sangat cocok untuk aplikasi berkecepatan tinggi seperti video streaming dan akses internet bergerak.
- `Efisiensi Spektrum :` Menggunakan OFDMA untuk mengatur spektrum radio dapat meningkatkan efisiensi dan mengurangi interferensi dalam lingkungan nirkabel yang padat.
- `Kualitas Layanan :` Standar ini diusulkan dengan tujuan memberikan kualitas layanan yang baik bahkan pada kecepatan tinggi dan mobilitas tinggi.

### Kelemahan:

- `Kurangnya Adopsi:` Salah satu kelemahan utama IEEE 802.20 adalah bahwa tidak banyak pihak telah mengadopsi standar ini secara luas, sehingga kurangnya ekosistem perangkat dan infrastruktur yang mendukungnya.
- `Persaingan dengan Teknologi Seluler:` Pada saat pengembangan standar ini, teknologi seluler seperti 3G dan kemudian 4G telah menjadi pilihan yang lebih umum dan mapan untuk konektivitas bergerak.
- `Kemajuan Teknologi Seluler:` Kemajuan dalam teknologi seluler, seperti 4G LTE dan kemudian 5G, telah mengungguli IEEE 802.20 dalam hal mobilitas dan kecepatan.

### Tantangan dalam menggunakan media transmisi dalam standar IEEE 802.20 termasuk:

- `Adopsi Standar:` Tantangan utama adalah adopsi standar ini oleh penyedia layanan, produsen perangkat, dan operator jaringan, yang memerlukan investasi besar dalam infrastruktur dan peralatan.
- `Interoperabilitas:` Memastikan interoperabilitas antara berbagai perangkat dan jaringan yang menggunakan standar ini adalah tantangan teknis yang signifikan.
- `Spektrum Radio:` Pencarian spektrum radio yang sesuai dan lisensi adalah hal yang perlu diperhatikan untuk mengoperasikan jaringan IEEE 802.20.

---

---

# Wireless Fundamental

## Spektrum

Dalam konteks jaringan nirkabel, "spektrum" mengacu pada kisaran frekuensi radio yang digunakan untuk transmisi data nirkabel. Spektrum ini mencakup berbagai frekuensi radio yang berbeda yang dapat digunakan oleh berbagai jenis perangkat dan layanan nirkabel.

## Bandwith

Band ini didefinisikan oleh rentang frekuensi tertentu yang dapat digunakan oleh perangkat nirkabel untuk mentransmisikan data atau sinyal komunikasi. Setiap band frekuensi memiliki karakteristik dan penggunaan khusus yang mungkin berbeda-beda.

```
Frekuensi yang terlalu tinggi seperti sinar-X, sinar gamma, dll., mempunyai energi yang sangat tinggi dan dapat berfungsi sebagai frekuensi komunikasi yang sangat baik.
Sayangnya, hal ini menimbulkan bahaya kesehatan yang serius dan dapat merusak ekosistem.
```

```
Gelombang frekuensi rendah seperti ultrasound, inframerah, dll., memiliki ketahanan yang buruk terhadap interferensi dan kecepatan data yang rendah.
Mungkin dapat diterima untuk komunikasi jarak pendek seperti mengaktifkan radio, televisi, dan peralatan rumah tangga lainnya, namun memerlukan jalur komunikasi yang bebas dari hambatan apa pun.
Kemudian muncul pertanyaan tentang receiver/antena yang cocok untuk menangkap dan mengirimkan frekuensi yang diperlukan.
```

Oleh karena itu, industri nirkabel mengidentifikasi `spektrum RF dari 100 MHz (UHF) hingga sekitar 30GHz untuk komunikasi nirkabel`.Di luar rentang tersebut, sebagian besar komunikasi nirkabel saat ini menggunakan rentang frekuensi 800 MHz hingga 3 GHz, yang diizinkan oleh Federal Communication Commission (FCC).

### Frekuensi radio

Frekuensi radio, (RF) adalah istilah yang mengacu pada arus bolak-balik, (AC) yang memiliki karakteristik sedemikian rupa sehingga, jika arus dimasukkan ke antena, medan/gelombang elektromagnetik (EM) dihasilkan sesuai untuk komunikasi nirkabel

### RF Behaviours

###### `Gain` : peningkatan amplitudo sinyal RF.

Biasanya menggunakan peningkat RF (RF Amplifier)
`memperkuat sinyal `atau antena gain tinggi digunakan untuk memfokuskan lebar pancaran sinyal guna meningkatkan amplitudo sinyalnya.

##### `LOSS`

Banyak hal yang dapat menyebabkan `hilangnya sinyal` RF, baik saat sinyal masih berada di dalam kabel sebagai sinyal listrik AC frekuensi tinggi maupun saat sinyal disebarkan sebagai gelombang radio melalui udara dengan antena.<br>

Objek yang berada langsung di jalur transmisi gelombang yang disebarkan dapat menyerap, memantulkan, atau menghancurkan sinyal RF

##### `Reflection`

Pemantulan
terjadi ketika gelombang elektromagnetik yang `merambat menimpa suatu benda yang lebih besar` dibandingkan dengan panjang gelombang rambatnya.<br>
Reflection erat kaitannya dengan multipath

##### `Refraction`

`Pembiasan` menggambarkan pembengkokan `gelombang radio saat melewati media dengan kepadatan berbeda`. Saat gelombang RF melewati media yang lebih padat (seperti genangan udara dingin yang terletak di lembah), gelombang tersebut akan dibengkokkan sedemikian rupa sehingga arahnya berubah.

##### `Scattering`

`Penyebaran / Penghamburan terjadi ketika` gelombang elektromagnetik (seperti gelombang radio atau gelombang cahaya) `bertemu dengan objek dan dihamburkan atau dibiaskan oleh objek tersebut`. Penyebaran terjadi ketika gelombang elektromagnetik tidak merambat dalam jalur yang lurus, tetapi dipantulkan atau dibiaskan dalam berbagai arah oleh objek yang berada di jalurnya.

##### `Absorption`

Penyerapan
`gelombang tersebut diserap atau diubah menjadi energi panas oleh material` atau medium yang dilewati oleh gelombang tersebut. Dalam konteks jaringan nirkabel dan komunikasi nirkabel, absorbsi dapat mengurangi intensitas sinyal dan mengurangi jangkauan atau kualitas sinyal

## Antena

`Antena mengubah energi listrik menjadi gelombang` RF pada antena pemancar, atau gelombang RF menjadi energi listrik pada antena penerima.<br>

Dimensi fisik antena, seperti panjangnya, berhubungan langsung dengan frekuensi antena dapat merambatkan gelombang atau menerima gelombang yang dirambatkan.

## Line of Sight (LOS)

`garis lurus dari objek` yang terlihat (pemancar) ke mata pengamat (penerima).

![Alt text](/assets/image.png)

## Fresnel Zone

Fresnel Zone menempati serangkaian area berbentuk ellipsoid konsentris di sekitar jalur LOS

Fresnel Zone penting untuk integritas link RF karena menentukan area di sekitar LOS yang dapat menimbulkan interferensi sinyal RF jika diblokir.

## ![Alt text](/assets/image1.png)

---

# Modulasi

proses mengubah sinyal informasi (data) dari bentuk aslinya menjadi bentuk yang cocok untuk transmisi melalui saluran komunikasi.

# Demodulasi

mengambil sinyal yang telah dimodulasi oleh gelombang pembawa dan mengembalikannya ke bentuk aslinya atau sinyal informasi.

## Jenis Modulasi

- `Amplitude Modulation (AM)`: Pada AM, amplitudo gelombang pembawa berubah sesuai dengan sinyal informasi. Ini umumnya digunakan dalam radio AM.

- `Frequency Modulation (FM)`: Pada FM, frekuensi gelombang pembawa berubah sesuai dengan sinyal informasi. Ini digunakan dalam radio FM.

- `Phase Modulation (PM)`: Pada PM, fase gelombang pembawa berubah sesuai dengan sinyal informasi. Ini digunakan dalam aplikasi seperti modulasi fasa kuadratur (QPSK) dalam komunikasi digital.

- `Modulasi Digital`: Dalam komunikasi digital, sinyal informasi (0 dan 1) diubah menjadi bentuk yang sesuai untuk transmisi. Ini termasuk modulasi seperti Amplitude Shift Key (ASK), Frequency Shift Key (FSK), Phase Shift Key (PSK), BPSK (Binary Phase-Shift Keying), QPSK (Quadrature Phase-Shift Keying), dan banyak lainnya

### Jenis Demodulasi :

- `Demodulasi AM`: Penerima AM akan mencari variasi amplitudo dalam sinyal untuk mengambil data audio yang ditransmisikan.

- `Demodulasi FM`: Penerima FM akan mencari variasi frekuensi dalam sinyal untuk mengembalikan sinyal audio.

- `Demodulasi QPSK`: Pada komunikasi digital, demodulasi QPSK akan mencari perubahan fase untuk menguraikan data digital yang ditransmisikan.

## Amplitude Shift Keying (ASK)

amplitudo gelombang pembawa (carrier wave) diubah untuk merepresentasikan data digital.

## Phase Shift Keying (PSK)

Dalam PSK, data digital direpresentasikan dengan mengubah fase gelombang pembawa (carrier wave).

# ANTENA

## Ada 3 jenis antena :

- Omni directional
- Semi-directional
- Highly-directional

## Omni directional

meradiasikan sinyal dalam semua arah secara merata, `seperti lingkaran`.
Contoh umum antena omni adalah antena dipole dan antena berbentuk batang, Wifi Rumah.

## Semi-directional (Antena Semi-Directional)

meradiasikan sinyal dengan pola radiasi yang `lebih fokus daripada antena omni`, tetapi masih mencakup beberapa sudut yang cukup besar.
Contoh antena semi-directional termasuk antena Yagi dan antena patch, Wifi ditaman, komunikasi antar kota.

## Highly-directional (Antena Highly-Directional)

memiliki pola `radiasi yang sangat fokus dan sempit`.
cocok untuk `jarak jauh` atau situasi di mana diperlukan koneksi yang sangat stabil dengan perangkat yang jauh.
