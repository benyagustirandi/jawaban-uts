# jawaban-uts 
No. 3a ukuran audio yaitu 352844 bytes <br />
No. 3b durasi audio yaitu 4.00 detik <br />
No. 3c sample rate audio yaitu 44100 Hz <br />
No. 3d frekuensi dari audio adalah: 200 Hz, 600 Hz, dan 1000 Hz <br />

Penjelasan: Pengolahan data untuk menentukan ukuran audio menggunakan package os.path.getsize <br />
yaitu untuk menampilkan ukuran file yang ada pada alamat path di sistem komputer <br />
penentuan durasi dari audio menggunakan hasil perbandingan frame audio dengan framerate dalam bentuk float <br />
menentukan sample rate menggunakan modul soindfile yang dapat membaca dan memutar audio dalam mp3 atau wav <br />
untuk melakukan analisa data menggunakan rfft yang merupakan bagian dari scipy.fft dimana modul ini melakukan <br />
diskrit transformasi dalam bentuk array dan hanya melakukan transformasi pada nilai real 'r' bukan bilangan kompleks <br />
selanjutnya nilai amplituodo didapat dari nilai absolut dari proses fft, sehingga dapat diplot amplitudo vs frekuensi <br />
dengan frekuensi yang ada pada audio yaitu 200 Hz, 600 Hz, dan 1000 Hz <br />



No. 4a ukuran gambar yaitu 3946 bytes <br />
No. 4b ukuran citra yang tersimpan adalah width (100) x Height (100) <br />
No. 4c format pixel dari gambar yaitu RGBA <br />
No. 4d frekuensi dari gambar dalam bentuk array pada file 20222017.inpynb <br />

Penjelasan: Pengolahan data untuk menentukan ukuran gambar menggunakan package os.path.getsize <br />
yaitu untuk menampilkan ukuran file yang ada pada alamat path di sistem komputer <br />
penentuan ukuran citra yang tersimpan dari gambar menggunakan modul PIL (pillow image Library) yang dapat membaca <br />
foto dengan berbagai format salah satunya adalah PNG, ukuran citra didapat dari width dan height, sedangkan untuk <br />
format citra menggunakan image mode. Selanjutnya analisa menggunakan fft dilakukan dengan merubah gambar dalam bentuk <br />
array, selanjutnya data array di fft dan dicari frekuensi untuk komponen x dan komponen y nya, selanjutnya data array <br />
dinormalisasi dan ditampilkan pada file 20222017.inpynb beserta hasil plot perbandingan gambar asli dan spektrum gambar fft. <br />


