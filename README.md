# KawanSurya   <img src="https://github.com/vinensius/KawanSurya/blob/main/ss/logo_round.png" alt="Image 1" width="50"> 
<img src="https://github.com/vinensius/KawanSurya/blob/main/ss/graphfeat.png" alt="Image 1" width="750">

KawanSurya merupakan sebuah aplikasi inovatif yang bertujuan untuk membantu individu di Indonesia membuat keputusan yang tepat tentang sistem PV atap. Aplikasi ini mempertimbangkan dua faktor penting yang dapat mempengaruhi keputusan untuk menginstall sistem PV atap: aspek teknis dan ekonomi.

Pertama-tama, KawanSurya menyediakan analisis rinci tentang aspek teknis dari sistem PV atap. Ini termasuk menilai potensi pemanfaatan energi listrik dari PV surya dibandingkan dengan konsumsi listrik secara keseluruhan. Aplikasi ini mempertimbangkan berbagai faktor seperti lokasi, orientasi, dan bayangan atap, serta efisiensi dan output dari panel surya yang digunakan. Dengan menganalisis faktor-faktor ini, KawanSurya dapat memberikan estimasi yang akurat tentang potensi output energi dan penghematan yang dapat dicapai melalui instalasi sistem PV atap.

Kedua, KawanSurya mengevaluasi kelayakan ekonomi investasi dalam sistem PV atap. Ini termasuk menganalisis biaya instalasi sistem, serta tingkat pengembalian investasi yang diharapkan dari waktu ke waktu. Aplikasi ini mempertimbangkan berbagai metrik keuangan seperti periode pengembalian modal, NPV, ROI. Selain itu, KawanSurya mengevaluasi regulasi untuk mengekspor listrik PV surya ke jaringan PLN, memastikan bahwa pengguna menyadari adanya hambatan atau insentif regulasi yang dapat mempengaruhi kelayakan ekonomi investasi mereka.

Secara keseluruhan, KawanSurya menyediakan analisis teknologi-ekonomi yang komprehensif tentang sistem PV atap di sistem On-Grid di Indonesia. Dengan mempertimbangkan aspek teknis dan ekonomi investasi, KawanSurya dapat membantu pengguna membuat keputusan yang tepat tentang instalasi sistem PV atap, memastikan bahwa mereka tidak hanya berkelanjutan secara lingkungan tetapi juga layak secara finansial.

<a href='https://play.google.com/store/apps/details?id=com.christophermarvel.pvcalc'><img alt='Get it on Google Play' src='https://play.google.com/intl/en_us/badges/static/images/badges/en_badge_web_generic.png' width=200/></a>

<img src="https://github.com/vinensius/KawanSurya/blob/main/ss/home.png" alt="Image 1" width="250"> <img src="https://github.com/vinensius/KawanSurya/blob/main/ss/beban.png" alt="Image 1" width="250"> <img src="https://github.com/vinensius/KawanSurya/blob/main/ss/lokasi.png" alt="Image 1" width="250">

- Parameter beban listrik akan menentukan besaran beban listrik yang dapat ditangani oleh output PV, beban listrik yang tidak tercakup oleh output PV, dan jumlah output PV yang diekspor kembali ke jaringan listrik.

- Parameter lokasi akan menentukan tingkat radiasi matahari yang ada di lokasi yang telah ditentukan oleh pengguna. Data radiasi matahari diambil dari database 2005-2016 PVGIS-SARAH yang juga memperhitungkan profil horizon. Radiasi matahari dan output PV akan berubah jika terdapat bukit atau gunung yang menghalangi sinar matahari pada beberapa periode dalam sehari. PVGIS dapat menghitung efek ini dengan menggunakan data tentang elevasi tanah. Namun, perhitungan ini tidak memperhitungkan bayangan dari benda-benda yang sangat dekat seperti rumah atau pohon.

- Parameter Teknis memungkinkan pengguna untuk menentukan beberapa spesifikasi sistem rooftop PV yang akan dipasang, dan ini sangat membantu KawanSurya dalam menghitung output rooftop PV serta perhitungan investasi rooftop PV.

- Parameter Ekonomis memungkinkan pengguna untuk menentukan spesifikasi sistem rooftop PV dari yang akan dipasang segi ekonomi, dan ini sangat membantu KawanSurya dalam menghitung perhitungan investasi rooftop PV.

<img src="https://github.com/vinensius/KawanSurya/blob/main/ss/teknis.png" alt="Image 1" width="250"> <img src="https://github.com/vinensius/KawanSurya/blob/main/ss/eko.png" alt="Image 1" width="250"> <img src="https://github.com/vinensius/KawanSurya/blob/main/ss/kalkulasi1.png" alt="Image 1" width="250">

Kalkulasi PV output menggunakan rumus Homer Energy,2023 :

<img src="https://github.com/vinensius/KawanSurya/blob/main/ss/rumuspvout.png" alt="Image 1" width="250">
<img src="https://github.com/vinensius/KawanSurya/blob/main/ss/rumustc.png" alt="Image 1" width="250">

Untuk derating factor KawanSurya menggunakan typical value (Sascha Lindig,Eurac Research, 2014):

<img src="https://github.com/vinensius/KawanSurya/blob/main/ss/derating.png" alt="Image 1" width="250">

Perhitungan investasi Net Savings dari pemasangan PV telah mencakup biaya O&amp;M, yang akan menjadi salah satu nilai dalam perhitungan payback period, NPV, dan ROI.

<img src="https://github.com/vinensius/KawanSurya/blob/main/ss/kalkulasi%202.png" alt="Image 1" width="250"> <img src="https://github.com/vinensius/KawanSurya/blob/main/ss/kalkulasi3.png" alt="Image 1" width="250"> <img src="https://github.com/vinensius/KawanSurya/blob/main/ss/kalukalsi4.png" alt="Image 1" width="250">

