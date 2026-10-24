saat saya memasukkan jumlah tiket 0, lebih dari 5, dan 1,5 form tidak dapat di submit karena yang diminta pada form yang telah dibuat pada kode program adalah min="1" dan max="5".
saat saya menguji format nim pada form yang telah saya buat menggunakan huruf dan lebih dari 6 angka tidak akan bisa di submit dikarenakan di dalam kode program telah di masukkan inputmode="numeric" pattern="[0-9]{6}"
Setelah ditambahkannya style css focus pada kolom saat di klik yang akan di isi akan berwarna menunjukkan apa yang ingin di isi.

                                 MATRIKS UJI DAN EKSPERIMEN KEGAGALAN
Kasus                   Harapan                             Status
Email kosong            Ditolak karena required             Lulus
Email abc               Ditolak karena bentuk email         Lulus
Email contoh valid      Email contoh valid                  Lulus
Jumlah 0 / 6            Ditolak                             Lulus
Jumlah 1 / 5            Diterima                            Lulus
Jumlah 1.5              Ditolak bila step=1                 Lulus
Kode 12345              Ditolak                             Lulus
Kode 001234             Diterima                            Lulus
Keyboard                Semua kontrol dapat dicapai         Lulus


                                         CEK VALIDATOR
1. Error pada id="luring"
    saya menambahkan spasi pada id=" luring" yang seharus nya tidak menggunakan spasi id="luring"
2. Error pada label for="kode"
    Masalah nya ada pada for yang harus sama persis dengan id. di situ saya membuat for="kode" dan  id="odke" tetapi seharus nya yang benar adalah id="odke" menjadi  id="kode"
3. Error pada label for="luring"  
    Terdapat spasi pada id=" luring" yang membuat for="luring" menganggapnya berbeda jadi yang seharus nya  id="luring"