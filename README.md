# KawanSurya   <img src="https://github.com/vinensius/KawanSurya/blob/main/ss/logo_round.png" alt="Image 1" width="50"> 
<img src="https://github.com/vinensius/KawanSurya/blob/main/ss/graphfeat.png" alt="Image 1" width="750">

KawanSurya adalah aplikasi analisis tekno-ekonomis rooftop PV untuk sistem On-Grid. Dua unsur penting yang dapat mempengaruhi keputusan pemasangan rooftop PV  yaitu aspek teknis (potensi pemanfaatan energi listrik dari solar PV dibandingkan komsumsi energi listrik secara keseluruhan) dan aspek ekonomis (justifikasi kelayakan investasi dan regulasi ekspor energi listrik solar PV ke jaringan PLN).

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

