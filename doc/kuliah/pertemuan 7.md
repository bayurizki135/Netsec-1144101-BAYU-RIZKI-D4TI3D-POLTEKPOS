IDS 

Sistem deteksi intrusi (IDS) adalah perangkat lunak yang berjalan pada server atau jaringan perangkat untuk memonitor dan melacak aktivitas jaringan. Dengan menggunakan IDS, administrator jaringan dapat mengkonfigurasi sistem untuk memonitor aktivitas jaringan untuk perilaku yang mencurigakan yang dapat menunjukkan upaya akses yang tidak sah

IPS 

Sistem Pencegahan Intrusi (IPS) seperti IDS mengikuti proses yang sama mengumpulkan dan mengidentifikasi data dan perilaku, dengan kemampuan tambahan untuk memblokir (mencegah) aktivitas. Network Based IPS (NIPS) dapat menahan semua trafik jaringan dan menginspeksi kelakuan dan kode yang mencurigakan. Karena menggunakan in-line model, performansi tinggi merupakan sebuah elemen krusial dari perangkat IPS untuk mencegah terjadinya bottleneck pada jaringan. Oleh karena itu, NIPS biasanya didesain menggunakan tiga komponen untuk mengakselerasi performansi bandwidth antara lain Network Chips (Network processor), FPGA Chips, ASIC Chips

 

 PEMBAHASAN 

 

Ada dua jenis IDS, yaitu:

    Network-based Intrusion Detection System (NIDS): Semua lalu lintas yang mengalir ke sebuah jaringan akan dianalisis untuk mencari apakah ada percobaan serangan atau penyusupan ke dalam sistem jaringan. NIDS umumnya terletak di dalam segmen jaringan penting di mana server berada atau terdapat pada “pintu masuk” jaringan. Kelemahan NIDS adalah bahwa NIDS agak rumit diimplementasikan dalam sebuah jaringan yang menggunakan switch Ethernet, meskipun beberapa vendor switch Ethernet sekarang telah menerapkan fungsi IDS di dalam switch buatannya untuk memonitor port atau koneksi.
    Host-based Intrusion Detection System (HIDS): Aktivitas sebuah host jaringan individual akan dipantau apakah terjadi sebuah percobaan serangan atau penyusupan ke dalamnya atau tidak. HIDS seringnya diletakkan pada server-server kritis di jaringan, seperti halnya firewall, web server, atau server yang terkoneksi ke Internet.

  Jenis-jenis IPS :

a. Host-based Intrusion Prevention System
Host Based IPS (HIPS) bekerja dengan memaksa sekelompok perangkat lunak fundamental untuk berkovensi secara konstan. Hal ini disebut dengan Application Binary Interface (ABI). Hampir tidak mungkin untuk membajak sebuah aplikasi tanpa memodifikasi Application Binary Interface, karena konvensi ini bersifat universal di antara aplikasi-aplikasi yang dimodifikasi.

HIPS merupakan sebuah system pecegahan yang terdiri dari banyak layer, menggunakan packet filtering, inspeksi status dan metode pencegahan intrusi yang bersifat real-time untuk menjaga host berada di bawah keadaan dari efisiensi performansi yang layak. Mekanisme kerjanya yaitu dengan mencegah kode-kode berbahaya yang memasuki host agar tidak dieksekusi tanpa perlu untuk mengecek threat signature.

b. Network Intrusion Prevention System
Network Based IPS (NIPS), yang juga disebut sebagai “In-line proactive protection”, menahan semua trafik jaringan dan menginspeksi kelakuan dan kode yang mencurigakan.
Karena menggunakan in-line model, performansi tinggi merupakan sebuah elemen krusial dari perangkat IPS untuk mencegah terjadinya bottleneck pada jaringan. Oleh karena itu, NIPS biasanya didesain menggunakan tiga komponen untuk mengakselerasi performansi bandwidth, yaitu :

1. Network Chips (Network processor)
2. FPGA Chips
3. ASIC Chips

 
