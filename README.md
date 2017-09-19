# Pie Echart

I. Jenis : Doughnut Chart

II. Option :

### **TITLE** ###
1.	Title : Text (string) -> untuk membuat judul.
2.	Title : textStyle (number) fontSize -> untuk mengubah ukuran text.
3.	Title : textStyle (string) color -> untuk mengubah warna.
4.	Title : textStyle (string) fontFamily -> mengubah jenis font.
5.	Title : textStyle (string) fontWeight bold-> membuat judul menjadi tebal.
6.	Title : textStyle (number) fontStyle italic-> untuk membuat gaya teks menjadi miring.
7.	Title : textBaseline (string) -> mengatur posisi teks secara vertical (top,middle,bottom).
8.	Title : link (string) -> untuk memindahkan halaman dari judul.
9.	Title : Target (string) blank -> untuk membuka halaman lain di tab baru.
            -Target (string) self -> untuk membuka halamanlain pada tab yang sama.
10.	Title : shadowOffsetX (number) -> jarak bayangan horizontal.
11.	Title : shadowOffsetY (number) -> jarak bayangan vertical.
12.	Title : shadowColor (color) -> menentukan warna shadow.
13.	Title : textAlign (string) -> menentukan letak teks (center,right,left).

### **TOOLTIP** ### 
1.	Tooltip : trigger (string) item -> digunakan untuk grafik yang tidak memiliki sumbu kategori seperti scatter chart atau pie chart.
2.	Tooltip : backgroundColor (color) -> untuk mengubah warna latar belakang lapisan apung tooltip.
Tooltip : formatter (string, function) -> Formatter dari layer floating tooltip yang mendukung template string dan fungsi callback.

### **GRID** ###
1.	Grid : left (string, number) -> jarak antara komponen grid dan sisi kiri.
2.	Grid : bottom (string, number) -> jarak antara komponen grid dan sisi bawah.
3.	Grid : top (string, number) ->jarak antara komponen grid dan sis atas.
4.	Grid : right (string, number) -> jaral antara komponen grid dan sisi kanan.
5.	Grid : show (string) true -> untuk menunjukan grid dalam koordinat.
6.  Grid : borderColor (color) -> untuk memberikan warna pada batas grid.

### **LEGEND** ###
1.	Legend : type (string) plain/scroll -> untuk tipe legend.
2.	Legend : orient (string) Vertical / horizontal -> Orientasi tata letak legend.
3.	Legend : x (string) right, left, center -> untuk posisi legend.
4.	Legend : left (string, number) -> Jarak objek dari sebelah kiri.
5.	Legend : right (string, number) -> Jarak  objek dari sebelah kanan.
6.	Legend : padding (number) -> membuat ruang di sekitar text.
7.	Legend : itemGap (number) -> jarak antara masing-masing legend, jarak horizontal dalam tata letak horizontal, dan jarak vertical  dalam dalam tata letal vertical.
8.	Legend : itemWidth (number) -> lebar gambar symbol legend.
9.	Legend : itemHeight (number) -> panjang gambar symbol legend
10.	Legend : data (object) -> Array data legenda. Item array biasanya merupakan nama yang mewakili string. (Jika itu adalah diagram lingkaran, itu juga bisa menjadi nama satu data dalam diagram lingkaran) dari rangkaian.
11.	Legend : selectedMode (string, boolean) -> mode legend yang dipilih, yang menggontrol apakah sama dapat ditampilkan secara bergantian dengan mengklik salah satu legend (single, multiple).
12. Legend : inactiveColor (color) -> warna legend pada saat tidak aktif.

### **SERIES** ### 
1.	Series : name (string) -> Nama seri yang digunakan untuk menampilkan tooltip.
2.	Series : type (string) -> Diagram lingkaran terutama digunakan untuk menunjukkan proporsi kategori yang berbeda. Setiap panjang busur mewakili proporsi kuantitas data.
3.	Series : radius (array) -> Radius bagan Pie, yang pertama adalah jari-jari dalam, dan yang kedua adalah jari-jari luar.
4.	Series : avoidLabelOverlap (Boolean) true/false -> Entah mengaktifkan strategi untuk menghindari label tumpang tindih. Default yang harus diaktifkan, yang akan memindahkan posisi label dalam kasus label yang tumpang tindih
5.	Series : Label; Normal; show (Boolean) true -> untuk menampilkan label ketika di klik.
6.	Series : Label; Normal; position (string) -> untuk posisi label.
7.	Series : Label; Emphasis; show (Boolean) false -> untuk menghilangkan label ketika di klik.
8.	Series : Label; Emphasis; textStyle ; fontSize (number) -> untuk mengatur ukuran text pada label.
9.	Series : Label; Emphasis; textStyle ; fontWeight (string) -> untuk menebalkan text pada label.
10.	Series ; labelLine; Normal; Show (Boolean) -> untuk menunjukkan garis panduan visual dalam status normal.

### **TOOLBOX** ###
1.  Toolbox : feature (object) : saveAsImage (object) -> untuk menyimpan gambar pada halaman web.
