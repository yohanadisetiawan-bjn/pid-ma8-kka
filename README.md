# pid-ma8-kka
Gemini
Panduan Gamifikasi Etika Digital HTML
Percakapan baru
Item Buatan Saya
Notebook

Panduan Sekolah Model Pembelajaran Mendalam, Koding, dan AI

Strategi Konstruksi Pengetahuan dan Pemahaman Murid
Notebook baru
Gem
Percakapan
Panduan Gamifikasi Etika Digital HTML
Model Pembelajaran VaKE: Nilai dan Pengetahuan
berdasarkan dokumen SKL2025, maka aturan kelulusan murid SMP seperti apa?
Dashboard Google Form Data Terbaru
Script Video Koding AI Kepala Sekolah
Rubrik Asesmen Informatika Format Check Chart
Analisis Grade Check Chart dan Adaptasi
Klasifikasi Konteks Pemanasan Global
Analisa PDF dan Modul Ajar
Aplikasi Teachable Machine Klasifikasi Gambar
Pitakon Lanjutan Kurikulum Informatika
Etika dan Hak Cipta Digital & AI
Rencana Pelatihan Produksi Konten Digital
Peran Orang Tua Dorong Berpikir Kritis

Setelan & bantuan
Percakapan dengan Gemini
buatkan panduan penggunaan gamifikasi pada file html yang telah disertakan, agar guru bisa menggunakan file htmlnya.

Desain gamifikasi berbasis Visual Novel yang Anda buat sangat menarik dan interaktif! Pendekatan simulasi peran (RPG) seperti ini adalah cara yang luar biasa untuk mengajarkan Etika Digital dan Hak Cipta, karena siswa tidak hanya menghafal teori, tetapi langsung dihadapkan pada studi kasus nyata.

Agar karya ini dapat diimplementasikan dengan mudah oleh rekan-rekan guru lainnya di ekosistem Kurikulum Merdeka, berikut adalah rancangan panduan penggunaan yang bisa Anda bagikan bersama file HTML tersebut.

Panduan Penggunaan Guru: Simulasi "Akademi Kreator"
Media pembelajaran interaktif "Petualangan Kreator Digital Beretika" dirancang untuk melatih pemahaman siswa terkait hak cipta, plagiarisme, dan etika atribusi karya digital. Media ini dapat difungsikan sebagai asesmen formatif yang menyenangkan.

1. Persiapan Teknis (Sebelum Kelas Dimulai)
Media ini dirancang sangat praktis dan tidak membutuhkan instalasi aplikasi khusus.

Akses File: File berformat .html ini dapat dibuka langsung menggunakan browser standar seperti Google Chrome, Microsoft Edge, atau Mozilla Firefox di laptop, Chromebook, maupun smartphone siswa.

Distribusi: Guru dapat membagikan file ini kepada siswa melalui grup WhatsApp kelas, Google Classroom, atau memindahkannya menggunakan flashdisk (karena game ini dapat berjalan 100% offline tanpa kuota internet).

Uji Coba: Sangat disarankan bagi guru untuk memainkan game ini minimal satu kali hingga mendapatkan sertifikat, agar memahami alur cerita dan karakter (Novita, Praditya, dan Dzakir).

2. Skenario Integrasi di Kelas (Pendekatan Pembelajaran Mendalam)
Penggunaan game ini akan sangat efektif jika dibagi ke dalam tiga etape pembelajaran:

Tahap Memahami (10 Menit): Awali kelas dengan diskusi singkat mengenai pengalaman siswa menggunakan lagu atau gambar dari internet untuk tugas sekolah. Bangun pemahaman dasar bahwa tidak semua yang ada di internet bebas digunakan tanpa aturan.

Tahap Mengaplikasi (20 Menit): Arahkan siswa untuk membuka file HTML dan memasukkan nama mereka. Biarkan mereka menavigasi skenario dan mengambil keputusan secara mandiri. Guru bertindak sebagai fasilitator yang mengawasi jalannya simulasi.

Tahap Merefleksi (10 Menit): Setelah siswa mendapatkan sertifikat di akhir permainan, minta beberapa siswa dengan predikat berbeda untuk menceritakan pilihan apa yang membuat mereka mendapatkan skor tersebut, dan apa pelajaran utamanya.

3. Panduan Tindak Lanjut Asesmen (Diferensiasi)
Di akhir permainan, siswa akan mendapatkan salah satu dari empat predikat. Guru dapat menggunakan hasil ini untuk menentukan langkah pembelajaran selanjutnya:

Predikat	Skor	Analisis & Tindak Lanjut Guru
Unggul	90 - 100	Siswa telah memahami etika digital dengan sangat baik. Diizinkan melanjutkan ke asesmen sumatif atau proyek pembuatan konten secara mandiri.
Maju	66 - 89	Pemahaman dasar sudah baik, namun ada detail atribusi yang mungkin terlewat. Berikan sedikit umpan balik penguatan sebelum mereka mengerjakan tugas akhir.
Berkembang	34 - 65	Siswa mulai paham, namun masih kesulitan membedakan batas antara "inspirasi" dan "plagiarisme". Perlu diskusi kelompok lanjutan.
Pra Berkembang	< 34	Siswa masih miskonsepsi mengenai hak cipta. Wajib diberikan pendampingan khusus (re-teaching) menggunakan contoh yang lebih sederhana.
4. Fitur Lanjutan: Kustomisasi Skenario (Opsional)
Bagi guru yang ingin mengubah jalan cerita atau soal tanpa harus mengedit kode HTML, game ini dilengkapi fitur Unggah Data KA.

Guru dapat membuat skenario baru menggunakan aplikasi Notepad (Windows) atau TextEdit (Mac) dengan format dasar seperti ini, lalu menyimpannya dengan ekstensi .txt:

JSON
{
  "intro1": {
    "npc": "Novita (KA)",
    "text": "Selamat datang di tantangan baru! Siap menguji pemahamanmu tentang jejak digital?",
    "options": [
      { "text": "Siap!", "next": "soal_1" }
    ]
  },
  "soal_1": {
    "npc": "Karakter Baru",
    "text": "Tuliskan pertanyaan kasus di sini...",
    "options": [
      { "text": "Jawaban Salah", "next": "respon_salah", "score": 0 },
      { "text": "Jawaban Benar", "next": "respon_benar", "score": 34 }
    ]
  }
}
Catatan: Pastikan blok pertama selalu diberi nama "intro1" agar game dapat memulai cerita dengan benar.

Panduan ini bisa Anda simpan dalam format PDF atau disematkan langsung sebagai halaman pendahuluan sebelum siswa/guru mengakses file utama.

Apakah Anda ingin saya buatkan draf skenario soal tambahan (file TXT/JSON) dengan topik spesifik lainnya, misalnya tentang keamanan siber atau perundungan siber (cyberbullying) untuk siswa jenjang SMP?

kembangkan soal file txt ini menjadi 25 soal yang memuat etika dan hak cipta sesuai bahan bacaan pada file pdf

Berikut adalah berkas JSON berisi 25 soal skenario gamifikasi yang telah dikembangkan secara komprehensif berdasarkan materi Etika Digital dan Hak Cipta. Setiap jawaban benar bernilai 4 poin (total skor maksimal 100).

Anda dapat menyalin seluruh kode di bawah ini dan menyimpannya sebagai file quest-etika.txt atau quest-etika.json, lalu mengunggahnya langsung ke dalam game simulasi Akademi Kreator.

JSON
{
  "intro1": {
    "npc": "Novita (KA)",
    "text": "Halo! Selamat datang di Akademi Kreator. Aku Novita, KA Pendampingmu. Hari ini kita akan membedah 25 kasus dari Agent-KA terkait etika digital dan hak cipta. Siap?",
    "options": [
      { "text": "Halo Novita! Aku siap menganalisis kasus mereka.", "next": "q1_Pandi" }
    ]
  },
  "q1_Pandi": {
    "npc": "Pandi (Agent-KA)",
    "text": "Lihat tugas video KKA-ku! Aku pakai lagu pop Indonesia dari Spotify utuh dari awal sampai akhir. Kan cuma buat tugas sekolah, jadi bebas Hak Cipta dong?",
    "options": [
      { "text": "Bebas kok! Asal nggak kamu jual, aman aja pakai lagu utuh.", "next": "q1_wrong", "score": 0 },
      { "text": "Hati-hati Pandi, meski buat pendidikan, pakai lagu utuh tanpa izin itu tetap melanggar Hak Cipta.", "next": "q1_correct", "score": 4 }
    ]
  },
  "q1_wrong": {
    "npc": "Novita (KA)",
    "text": "Tanggapanmu keliru. Meskipun untuk pendidikan (tugas sekolah), menggunakan karya utuh milik orang lain tanpa izin tetap melanggar Hak Cipta[cite: 3].",
    "options": [
      { "text": "Baiklah, aku akan lebih teliti. Lanjut ke kasus berikutnya!", "next": "q2_Dzakir" }
    ]
  },
  "q1_correct": {
    "npc": "Novita (KA)",
    "text": "Tepat sekali! Pencipta lagu memiliki hak eksklusif[cite: 3]. Lebih aman menggunakan musik berlisensi bebas royalti.",
    "options": [
      { "text": "Ayo kita lanjut temui Dzakir!", "next": "q2_Dzakir" }
    ]
  },
  "q2_Dzakir": {
    "npc": "Dzakir (Agent-KA)",
    "text": "Aku nemu artikel bagus di blog. Aku copy-paste aja semua paragrafnya persis, lalu kuganti nama penulisnya jadi namaku.",
    "options": [
      { "text": "Dzakir, itu namanya Plagiarisme! Itu penjiplakan karya.", "next": "q2_correct", "score": 4 },
      { "text": "Wah, cerdas juga. Cari inspirasi emang gampang di internet.", "next": "q2_wrong", "score": 0 }
    ]
  },
  "q2_wrong": {
    "npc": "Novita (KA)",
    "text": "Awas! Menyalin karya orang lain, seperti teks artikel, dan mengakuinya sebagai milik sendiri adalah pelanggaran etika yang serius[cite: 3].",
    "options": [
      { "text": "Aku baru paham. Lanjut Novita.", "next": "q3_Pandi" }
    ]
  },
  "q2_correct": {
    "npc": "Novita (KA)",
    "text": "Luar biasa! Plagiarisme adalah pelanggaran serius, kita harus selalu memberikan kredit yang tepat kepada pembuat asli[cite: 3].",
    "options": [
      { "text": "Tentu saja! Lanjut ke kasus ketiga.", "next": "q3_Pandi" }
    ]
  },
  "q3_Pandi": {
    "npc": "Pandi (Agent-KA)",
    "text": "Aku mau cantumin atribusi dari gambar Unsplash nih. Cukup tulis 'Sumber: Google' atau 'Sumber: Internet' kan?",
    "options": [
      { "text": "Ya, Google itu kan mesin pencari tempat kita dapet gambarnya.", "next": "q3_wrong", "score": 0 },
      { "text": "Salah! Kamu harus nulis Nama Kreator asli, Judul, dan link sumbernya.", "next": "q3_correct", "score": 4 }
    ]
  },
  "q3_wrong": {
    "npc": "Novita (KA)",
    "text": "Kurang tepat. Google hanya mesin pencari. Audit atribusi yang baik harus mencantumkan detail spesifik pembuatnya[cite: 3].",
    "options": [
      { "text": "Oke, aku ingat. Selanjutnya?", "next": "q4_Dzakir" }
    ]
  },
  "q3_correct": {
    "npc": "Novita (KA)",
    "text": "Sempurna! Atribusi yang jelas menunjukkan bahwa kita adalah kreator yang jujur dan profesional[cite: 3].",
    "options": [
      { "text": "Mantap! Apa tantangan selanjutnya?", "next": "q4_Dzakir" }
    ]
  },
  "q4_Dzakir": {
    "npc": "Dzakir (Agent-KA)",
    "text": "Aku baru saja punya 'ide' bikin sistem informasi sekolah. Apa ide di kepalaku ini otomatis dilindungi hak cipta?",
    "options": [
      { "text": "Tentu, siapa yang punya ide pertama, dia yang pegang hak cipta.", "next": "q4_wrong", "score": 0 },
      { "text": "Belum. Ide tidak dilindungi, yang dilindungi adalah karya nyata seperti kodenya.", "next": "q4_correct", "score": 4 }
    ]
  },
  "q4_wrong": {
    "npc": "Novita (KA)",
    "text": "Salah. Hak cipta tidak melindungi ide, fakta, atau konsep matematis[cite: 3].",
    "options": [
      { "text": "Oh, jadi harus diwujudkan dulu ya. Lanjut!", "next": "q5_Pandi" }
    ]
  },
  "q4_correct": {
    "npc": "Novita (KA)",
    "text": "Benar! Ide tidak dilindungi, tetapi karya arsitektur perangkat lunak atau kode sumber yang sudah dibangun otomatis dilindungi[cite: 3].",
    "options": [
      { "text": "Sip! Ayo ke soal berikutnya.", "next": "q5_Pandi" }
    ]
  },
  "q5_Pandi": {
    "npc": "Pandi (Agent-KA)",
    "text": "Sebenarnya, berapa lama sih masa berlaku perlindungan hak cipta di Indonesia setelah karya itu dibuat?",
    "options": [
      { "text": "Seumur hidup pencipta ditambah 70 tahun setelah meninggal.", "next": "q5_correct", "score": 4 },
      { "text": "Berlaku selamanya tanpa batas waktu.", "next": "q5_wrong", "score": 0 }
    ]
  },
  "q5_wrong": {
    "npc": "Novita (KA)",
    "text": "Kurang tepat. Di Indonesia, perlindungan ini umumnya berlaku seumur hidup pencipta ditambah 70 tahun setelah mereka meninggal[cite: 3].",
    "options": [
      { "text": "Cukup lama juga ya. Lanjut!", "next": "q6_Dzakir" }
    ]
  },
  "q5_correct": {
    "npc": "Novita (KA)",
    "text": "Benar sekali! Perlindungan umumnya berlaku seumur hidup pencipta ditambah puluhan tahun, tepatnya 70 tahun di Indonesia[cite: 3].",
    "options": [
      { "text": "Wah, pengetahuan baru! Lanjut yuk.", "next": "q6_Dzakir" }
    ]
  },
  "q6_Dzakir": {
    "npc": "Dzakir (Agent-KA)",
    "text": "Aku nemu musik dengan lisensi Creative Commons 'CC BY'. Artinya aku boleh pakai musik ini dengan syarat apa?",
    "options": [
      { "text": "Boleh dipakai asal mencantumkan atribusi pembuatnya.", "next": "q6_correct", "score": 4 },
      { "text": "Boleh dipakai tapi dilarang keras untuk video YouTube.", "next": "q6_wrong", "score": 0 }
    ]
  },
  "q6_wrong": {
    "npc": "Novita (KA)",
    "text": "Keliru. Lisensi CC BY mengharuskan pengguna hanya memberikan atribusi yang sesuai[cite: 3].",
    "options": [
      { "text": "Paham, kuncinya di atribusi. Lanjut!", "next": "q7_Pandi" }
    ]
  },
  "q6_correct": {
    "npc": "Novita (KA)",
    "text": "Tepat! Lisensi CC BY memungkinkan karya digunakan asalkan penggunanya memberikan atribusi kepada pencipta asli[cite: 3].",
    "options": [
      { "text": "Oke, pertanyaan ketujuh!", "next": "q7_Pandi" }
    ]
  },
  "q7_Pandi": {
    "npc": "Pandi (Agent-KA)",
    "text": "Kalau lisensinya ada tambahan 'NC' jadi 'CC BY-NC', apa aku boleh pakai gambar itu untuk stiker jualan?",
    "options": [
      { "text": "Tentu saja boleh, kan udah ngasih nama pembuatnya.", "next": "q7_wrong", "score": 0 },
      { "text": "Tidak boleh, 'NC' itu Non-Commercial, melarang penggunaan untuk tujuan komersial.", "next": "q7_correct", "score": 4 }
    ]
  },
  "q7_wrong": {
    "npc": "Novita (KA)",
    "text": "Awas! Lisensi CC BY-NC secara tegas melarang penggunaan karya tersebut untuk tujuan komersial seperti berjualan[cite: 3].",
    "options": [
      { "text": "Bahaya kalau sampai didenda. Next!", "next": "q8_Dzakir" }
    ]
  },
  "q7_correct": {
    "npc": "Novita (KA)",
    "text": "Hebat! CC BY-NC memang melarang penggunaan untuk tujuan komersial, meskipun atribusi sudah diberikan[cite: 3].",
    "options": [
      { "text": "Analisa yang tajam. Lanjut Novita!", "next": "q8_Dzakir" }
    ]
  },
  "q8_Dzakir": {
    "npc": "Dzakir (Agent-KA)",
    "text": "Aku pakai kode program dari Github dengan lisensi Open Source (MIT). Berarti aku bebas pakai tanpa aturan apapun kan?",
    "options": [
      { "text": "Benar, Open Source berarti kode itu murni bebas aturan.", "next": "q8_wrong", "score": 0 },
      { "text": "Salah, setiap lisensi Open Source tetap memiliki ketentuan atribusi yang harus dipatuhi.", "next": "q8_correct", "score": 4 }
    ]
  },
  "q8_wrong": {
    "npc": "Novita (KA)",
    "text": "Kurang tepat. Open Source bukan berarti bebas dari aturan; setiap lisensi tetap memiliki ketentuan atribusi dan modifikasi[cite: 3].",
    "options": [
      { "text": "Oh, tetap harus baca lisensinya ya. Lanjut!", "next": "q9_Pandi" }
    ]
  },
  "q8_correct": {
    "npc": "Novita (KA)",
    "text": "Betul sekali. Open Source bukan berarti bebas dari aturan; ketentuan atribusi dan modifikasi tetap harus dipatuhi[cite: 3].",
    "options": [
      { "text": "Selalu periksa lisensinya. Kasus selanjutnya!", "next": "q9_Pandi" }
    ]
  },
  "q9_Pandi": {
    "npc": "Pandi (Agent-KA)",
    "text": "Untuk tugas video berita, aku ambil sedikit cuplikan siaran berita TV. Ini melanggar hukum nggak sih?",
    "options": [
      { "text": "Aman, itu termasuk Penggunaan Wajar (Fair Use) untuk tujuan pelaporan dan pendidikan.", "next": "q9_correct", "score": 4 },
      { "text": "Melanggar! Tidak peduli sedikit atau banyak, tidak boleh sama sekali.", "next": "q9_wrong", "score": 0 }
    ]
  },
  "q9_wrong": {
    "npc": "Novita (KA)",
    "text": "Hukum Hak Cipta memiliki pengecualian yang disebut Penggunaan Wajar (Fair Use) yang mengizinkan penggunaan terbatas untuk pendidikan, pelaporan berita, atau kritik[cite: 3].",
    "options": [
      { "text": "Jadi tergantung porsi yang diambil ya. Lanjut!", "next": "q10_Dzakir" }
    ]
  },
  "q9_correct": {
    "npc": "Novita (KA)",
    "text": "Tepat! Penggunaan Wajar (Fair Use) mengizinkan penggunaan terbatas dari materi berhak cipta untuk tujuan pendidikan dan pelaporan berita[cite: 3].",
    "options": [
      { "text": "Porsinya harus dijaga agar tetap wajar. Selanjutnya?", "next": "q10_Dzakir" }
    ]
  },
  "q10_Dzakir": {
    "npc": "Dzakir (Agent-KA)",
    "text": "Gimana sih cara paling gampang cari gambar legal langsung dari mesin pencari Google?",
    "options": [
      { "text": "Gunakan menu Tools, lalu pilih Usage rights, dan klik Creative Commons licenses.", "next": "q10_correct", "score": 4 },
      { "text": "Ketik saja 'gambar bebas gratis' lalu ambil dari hasil pencarian teratas.", "next": "q10_wrong", "score": 0 }
    ]
  },
  "q10_wrong": {
    "npc": "Novita (KA)",
    "text": "Itu berisiko tinggi. Cara yang benar di Google adalah dengan memilih menu Tools -> User Rights -> Creative Commons licenses[cite: 3].",
    "options": [
      { "text": "Aku akan pakai fitur Tools mulai sekarang. Lanjut!", "next": "q11_Pandi" }
    ]
  },
  "q10_correct": {
    "npc": "Novita (KA)",
    "text": "Benar! Memanfaatkan filter Tools -> User Rights pada Google adalah cara cepat menyaring aset berlisensi Creative Commons[cite: 3].",
    "options": [
      { "text": "Fitur yang sangat membantu. Lanjut pertanyaan 11!", "next": "q11_Pandi" }
    ]
  },
  "q11_Pandi": {
    "npc": "Pandi (Agent-KA)",
    "text": "Selain lewat Google, situs apa yang terpercaya untuk mencari foto berkualitas tinggi yang aman dan gratis?",
    "options": [
      { "text": "Situs Unsplash, Pexels, atau Pixabay.", "next": "q11_correct", "score": 4 },
      { "text": "Situs media sosial milik artis ternama.", "next": "q11_wrong", "score": 0 }
    ]
  },
  "q11_wrong": {
    "npc": "Novita (KA)",
    "text": "Salah besar! Foto di media sosial dilindungi hak cipta penuh. Gunakan situs seperti Unsplash atau Pixabay yang menyediakan foto bebas royalti[cite: 3].",
    "options": [
      { "text": "Oh iya, Unsplash dan Pixabay. Lanjut!", "next": "q12_Dzakir" }
    ]
  },
  "q11_correct": {
    "npc": "Novita (KA)",
    "text": "Sangat tepat! Unsplash dan Pixabay adalah situs yang menyediakan foto resolusi tinggi serta vektor bebas royalti[cite: 3].",
    "options": [
      { "text": "Catat! Situs apa lagi nih untuk kasus lain?", "next": "q12_Dzakir" }
    ]
  },
  "q12_Dzakir": {
    "npc": "Dzakir (Agent-KA)",
    "text": "Kalau aku butuh aset berupa potongan video gratis untuk background vlog, situs apa yang cocok?",
    "options": [
      { "text": "Situs Coverr atau Mixkit.", "next": "q12_correct", "score": 4 },
      { "text": "Unduh saja dari video YouTube orang lain pakai aplikasi downloader.", "next": "q12_wrong", "score": 0 }
    ]
  },
  "q12_wrong": {
    "npc": "Novita (KA)",
    "text": "Jangan pernah mengunduh video orang lain tanpa izin! Lebih baik gunakan situs Coverr atau Mixkit yang menawarkan aset video gratis[cite: 3].",
    "options": [
      { "text": "Aku nggak akan mengulanginya. Lanjut Novita.", "next": "q13_Pandi" }
    ]
  },
  "q12_correct": {
    "npc": "Novita (KA)",
    "text": "Tepat! Coverr dan Mixkit adalah situs penyedia video stok gratis yang aman untuk penggunaan non-komersial maupun komersial[cite: 3].",
    "options": [
      { "text": "Banyak pilihan situs aman ya. Apa lagi?", "next": "q13_Pandi" }
    ]
  },
  "q13_Pandi": {
    "npc": "Pandi (Agent-KA)",
    "text": "Aku lagi ngumpulin data kelas, lucu kali ya kalau aku pakai foto diam-diam temanku buat dijadiin meme untuk grup sekolah?",
    "options": [
      { "text": "Boleh aja, yang penting kan buat lucu-lucuan di grup sendiri.", "next": "q13_wrong", "score": 0 },
      { "text": "Jangan! Itu melanggar privasi, jangan menyebarkan data pribadi tanpa izin eksplisit.", "next": "q13_correct", "score": 4 }
    ]
  },
  "q13_wrong": {
    "npc": "Novita (KA)",
    "text": "Itu berbahaya! Sangat penting untuk menghormati privasi individu dan tidak menyebarkan data pribadi (seperti foto) tanpa izin eksplisit[cite: 3].",
    "options": [
      { "text": "Wah, bercandaan bisa jadi serius. Lanjut!", "next": "q14_Dzakir" }
    ]
  },
  "q13_correct": {
    "npc": "Novita (KA)",
    "text": "Kamu benar! Menghormati privasi individu sangat krusial; data pribadi tidak boleh disebarkan tanpa izin eksplisit[cite: 3].",
    "options": [
      { "text": "Setuju, harus saling menghormati. Next!", "next": "q14_Dzakir" }
    ]
  },
  "q14_Dzakir": {
    "npc": "Dzakir (Agent-KA)",
    "text": "Memangnya kenapa sih kalau aku upload karya bajakan ke internet? Kan nanti juga ketumpuk sama postingan orang lain.",
    "options": [
      { "text": "Nggak apa-apa, orang internet gampang lupa kok.", "next": "q14_wrong", "score": 0 },
      { "text": "Karyamu itu meninggalkan jejak digital permanen yang bisa memengaruhi reputasi masa depanmu.", "next": "q14_correct", "score": 4 }
    ]
  },
  "q14_wrong": {
    "npc": "Novita (KA)",
    "text": "Itu pola pikir yang salah. Karya digital yang diunggah akan meninggalkan rekam jejak permanen yang dapat memengaruhi reputasi profesional di masa depan[cite: 3].",
    "options": [
      { "text": "Menyeramkan juga jejak digital itu. Lanjut!", "next": "q15_Pandi" }
    ]
  },
  "q14_correct": {
    "npc": "Novita (KA)",
    "text": "Sangat bijak! Setiap publikasi proyek digital meninggalkan rekam jejak permanen yang akan berdampak pada reputasi akademis dan profesional di masa depan[cite: 3].",
    "options": [
      { "text": "Harus jaga jejak digital yang positif! Lanjut soal 15.", "next": "q15_Pandi" }
    ]
  },
  "q15_Pandi": {
    "npc": "Pandi (Agent-KA)",
    "text": "Aku download desain template orang, lalu aku cuma ubah warnanya sedikit. Boleh kan aku bilang ini karya orisinal buatanku 100%?",
    "options": [
      { "text": "Tentu, karena kamu udah ngasih sentuhan warna unik.", "next": "q15_wrong", "score": 0 },
      { "text": "Tidak boleh, mengklaim modifikasi kecil dari karya pihak ketiga sebagai inovasi mandiri melanggar orisinalitas.", "next": "q15_correct", "score": 4 }
    ]
  },
  "q15_wrong": {
    "npc": "Novita (KA)",
    "text": "Keliru. Etika orisinalitas melarang kita mengklaim modifikasi kecil dari karya pihak ketiga sebagai inovasi yang sepenuhnya mandiri[cite: 3].",
    "options": [
      { "text": "Oh, berarti tetap harus kasih kredit ke pembuat template asli. Lanjut!", "next": "q16_Dzakir" }
    ]
  },
  "q15_correct": {
    "npc": "Novita (KA)",
    "text": "Betul sekali! Penting untuk tidak mengklaim modifikasi kecil dari karya pihak ketiga sebagai inovasi yang sepenuhnya mandiri demi menjunjung tinggi orisinalitas[cite: 3].",
    "options": [
      { "text": "Integritas nomor satu! Pertanyaan berikutnya?", "next": "q16_Dzakir" }
    ]
  },
  "q16_Dzakir": {
    "npc": "Dzakir (Agent-KA)",
    "text": "Di tim STEM, aku yang ngetik laporan, Pandi yang bikin kodenya. Waktu dipublish, aku taruh namaku aja ya sebagai pembuat tunggal?",
    "options": [
      { "text": "Boleh, kan kamu ketua kelompoknya.", "next": "q16_wrong", "score": 0 },
      { "text": "Tidak etis, harus ada transparansi pembagian kredit yang adil atas kontribusi setiap individu.", "next": "q16_correct", "score": 4 }
    ]
  },
  "q16_wrong": {
    "npc": "Novita (KA)",
    "text": "Itu tindakan tidak adil. Etika kolaborasi menuntut adanya transparansi dalam penentuan kepemilikan dan pembagian kredit yang adil atas kontribusi individu[cite: 3].",
    "options": [
      { "text": "Maafkan aku Pandi, jasamu akan kutulis. Lanjut!", "next": "q17_Pandi" }
    ]
  },
  "q16_correct": {
    "npc": "Novita (KA)",
    "text": "Sikap pemimpin yang baik! Kolaborasi tim yang etis harus memastikan transparansi dan pembagian kredit yang adil untuk masing-masing individu[cite: 3].",
    "options": [
      { "text": "Semua anggota berharga! Lanjut ke soal publikasi.", "next": "q17_Pandi" }
    ]
  },
  "q17_Pandi": {
    "npc": "Pandi (Agent-KA)",
    "text": "Proyek aplikasi kita udah selesai nih. Sebelum di-upload ke internet agar bisa dipakai banyak orang, langkah terakhir apa yang wajib dilakukan?",
    "options": [
      { "text": "Lakukan peninjauan akhir untuk memastikan tidak ada materi berhak cipta pihak lain secara ilegal.", "next": "q17_correct", "score": 4 },
      { "text": "Langsung unggah saja mumpung aplikasinya tidak error.", "next": "q17_wrong", "score": 0 }
    ]
  },
  "q17_wrong": {
    "npc": "Novita (KA)",
    "text": "Jangan terburu-buru! Tanggung jawab publikasi mengharuskan peninjauan akhir untuk memastikan tidak ada materi berhak cipta pihak lain yang dimasukkan secara ilegal[cite: 3].",
    "options": [
      { "text": "Baik, akan aku cek ulang asetnya. Selanjutnya?", "next": "q18_Novita" }
    ]
  },
  "q17_correct": {
    "npc": "Novita (KA)",
    "text": "Jawaban yang sangat bertanggung jawab! Peninjauan akhir sangat penting sebelum mengunggah karya ke platform publik[cite: 3].",
    "options": [
      { "text": "Siap! Masuk ke soal berikutnya.", "next": "q18_Novita" }
    ]
  },
  "q18_Novita": {
    "npc": "Novita (KA)",
    "text": "Sekarang giliranku bertanya. Dalam hukum di Indonesia, hak yang melekat pada pencipta agar namanya tetap dicantumkan pada karya disebut apa?",
    "options": [
      { "text": "Hak Ekonomi.", "next": "q18_wrong", "score": 0 },
      { "text": "Hak Moral.", "next": "q18_correct", "score": 4 }
    ]
  },
  "q18_wrong": {
    "npc": "Novita (KA)",
    "text": "Kurang tepat. Kewajiban mencantumkan nama berkaitan erat dengan Hak Moral yang melekat pada pencipta karya[cite: 3].",
    "options": [
      { "text": "Hak Moral, aku ingat sekarang. Lanjut!", "next": "q19_Dzakir" }
    ]
  },
  "q18_correct": {
    "npc": "Novita (KA)",
    "text": "Luar biasa! Itu adalah Hak Moral, yaitu hak pencipta untuk tetap dicantumkan namanya pada karyanya sebagai bentuk penghormatan[cite: 3].",
    "options": [
      { "text": "Tentu, apresiasi itu penting. Lanjut!", "next": "q19_Dzakir" }
    ]
  },
  "q19_Dzakir": {
    "npc": "Dzakir (Agent-KA)",
    "text": "Aku dengar untuk atribusi lengkap standar internasional itu pakai metode TASL. Kepanjangannya apa sih?",
    "options": [
      { "text": "Title, Author, Source, License.", "next": "q19_correct", "score": 4 },
      { "text": "Time, Audio, Sound, Link.", "next": "q19_wrong", "score": 0 }
    ]
  },
  "q19_wrong": {
    "npc": "Novita (KA)",
    "text": "Bukan itu! Metode TASL adalah singkatan dari Title (Judul), Author (Pencipta), Source (Sumber), dan License (Lisensi)[cite: 3].",
    "options": [
      { "text": "Oh, Title Author Source License. Oke lanjut!", "next": "q20_Pandi" }
    ]
  },
  "q19_correct": {
    "npc": "Novita (KA)",
    "text": "Tepat 100%! Formula TASL (Title, Author, Source, License) adalah standar internasional untuk atribusi lengkap[cite: 3].",
    "options": [
      { "text": "Sangat mudah diingat! Pertanyaan selanjutnya?", "next": "q20_Pandi" }
    ]
  },
  "q20_Pandi": {
    "npc": "Pandi (Agent-KA)",
    "text": "Di elemen Source dan License pada metode TASL, apa wujud data yang biasanya kita tuliskan?",
    "options": [
      { "text": "Cukup tulis 'Dari Internet' dan 'Gratis'.", "next": "q20_wrong", "score": 0 },
      { "text": "Source berupa link/URL website aslinya, dan License diisi jenis lisensinya seperti CC BY 4.0.", "next": "q20_correct", "score": 4 }
    ]
  },
  "q20_wrong": {
    "npc": "Novita (KA)",
    "text": "Itu terlalu ambigu. Source (Sumber) harus berupa tempat karya ditemukan seperti link/URL, dan License (Lisensi) menjelaskan di bawah aturan apa karya dibagikan[cite: 3].",
    "options": [
      { "text": "Baiklah, link URL harus masuk. Lanjut 5 soal terakhir!", "next": "q21_Dzakir" }
    ]
  },
  "q20_correct": {
    "npc": "Novita (KA)",
    "text": "Sempurna! Source mencantumkan lokasi/URL karya ditemukan, sedangkan License menunjukkan di bawah lisensi apa karya tersebut dibagikan[cite: 3].",
    "options": [
      { "text": "Sudah semakin ahli nih! Lanjut ke soal 21.", "next": "q21_Dzakir" }
    ]
  },
  "q21_Dzakir": {
    "npc": "Dzakir (Agent-KA)",
    "text": "Apakah ada kondisi di mana kita memakai gambar lama sekali, tapi tidak perlu menuliskan atribusinya?",
    "options": [
      { "text": "Ada, yaitu ketika masa berlaku hak ciptanya telah habis dan masuk ke Domain Publik.", "next": "q21_correct", "score": 4 },
      { "text": "Tidak ada, semua gambar sejak zaman dulu wajib dikasih atribusi selamanya.", "next": "q21_wrong", "score": 0 }
    ]
  },
  "q21_wrong": {
    "npc": "Novita (KA)",
    "text": "Ada pengecualiannya! Atribusi tidak diperlukan jika masa berlaku hak cipta karya tersebut telah habis, yang artinya sudah masuk dalam ranah Domain Publik[cite: 3].",
    "options": [
      { "text": "Oh begitu pengecualiannya. Lanjut!", "next": "q22_Pandi" }
    ]
  },
  "q21_correct": {
    "npc": "Novita (KA)",
    "text": "Tepat! Saat masa berlaku hak ciptanya telah habis, karya tersebut menjadi Domain Publik sehingga atribusi tidak lagi diwajibkan[cite: 3].",
    "options": [
      { "text": "Informasi yang sangat berguna! Selanjutnya?", "next": "q22_Pandi" }
    ]
  },
  "q22_Pandi": {
    "npc": "Pandi (Agent-KA)",
    "text": "Aku lihat di website ada gambar dengan tulisan lisensi 'CC0'. Maksud angka nol di situ apa ya?",
    "options": [
      { "text": "Maksudnya Creative Commons Zero, pencipta merelakan karyanya digunakan tanpa syarat apa pun, termasuk bebas atribusi.", "next": "q22_correct", "score": 4 },
      { "text": "Itu artinya karya tidak boleh disentuh atau diedit sama sekali oleh orang lain.", "next": "q22_wrong", "score": 0 }
    ]
  },
  "q22_wrong": {
    "npc": "Novita (KA)",
    "text": "Salah terka! CC0 berarti Creative Commons Zero, di mana sang pencipta merelakan karyanya digunakan tanpa syarat apa pun[cite: 3].",
    "options": [
      { "text": "Wah, baik banget pembuatnya. Lanjut soal 23!", "next": "q23_Dzakir" }
    ]
  },
  "q22_correct": {
    "npc": "Novita (KA)",
    "text": "Hebat! Lisensi CC0 (Creative Commons Zero) berarti pencipta secara penuh merelakan karyanya untuk digunakan tanpa syarat[cite: 3].",
    "options": [
      { "text": "Sangat membantu kreator digital. Apa pertanyaan berikutnya?", "next": "q23_Dzakir" }
    ]
  },
  "q23_Dzakir": {
    "npc": "Dzakir (Agent-KA)",
    "text": "Di laporan ilmiahku, aku menulis fakta umum bahwa 'Matahari terbit dari timur'. Aku bingung, fakta ini harus kucantumkan atribusi ke siapa?",
    "options": [
      { "text": "Atribusi ke ilmuwan pertama yang menemukan teori itu.", "next": "q23_wrong", "score": 0 },
      { "text": "Tidak perlu atribusi, karena itu merupakan fakta umum yang sudah diketahui publik.", "next": "q23_correct", "score": 4 }
    ]
  },
  "q23_wrong": {
    "npc": "Novita (KA)",
    "text": "Tidak perlu se-kaku itu. Atribusi tidak diperlukan jika karya atau informasi tersebut merupakan ide umum atau fakta yang diketahui publik[cite: 3].",
    "options": [
      { "text": "Masuk akal. Ayo sisa dua soal terakhir!", "next": "q24_Pandi" }
    ]
  },
  "q23_correct": {
    "npc": "Novita (KA)",
    "text": "Tepat! Ide umum atau fakta yang telah diketahui publik tidak memerlukan proses atribusi[cite: 3].",
    "options": [
      { "text": "Jelas sekali. Lanjut soal 24!", "next": "q24_Pandi" }
    ]
  },
  "q24_Pandi": {
    "npc": "Pandi (Agent-KA)",
    "text": "Saat aku memodifikasi contoh kode program Arduino dari internet untuk proyek STEM-ku, di mana sebaiknya aku meletakkan atribusi TASL-nya?",
    "options": [
      { "text": "Sisipkan teks atribusi TASL di dalam baris komentar (comment code) di dalam file kode sumber tersebut.", "next": "q24_correct", "score": 4 },
      { "text": "Tulis pakai spidol di atas papan perangkat keras Arduino-nya.", "next": "q24_wrong", "score": 0 }
    ]
  },
  "q24_wrong": {
    "npc": "Novita (KA)",
    "text": "Itu kurang tepat secara format digital. Dalam pengembangan perangkat lunak, atribusi standar diletakkan sebagai teks komentar di dalam kode program (source code)[cite: 3].",
    "options": [
      { "text": "Baiklah, akan kurapikan di dalam kodenya. Soal terakhir!", "next": "q25_Dzakir" }
    ]
  },
  "q24_correct": {
    "npc": "Novita (KA)",
    "text": "Sangat rapi dan etis! Mencantumkan TASL di dalam baris komentar kode program adalah bentuk atribusi yang paling baik di ranah rekayasa perangkat lunak[cite: 3].",
    "options": [
      { "text": "Ayo selesaikan soal terakhir, Dzakir!", "next": "q25_Dzakir" }
    ]
  },
  "q25_Dzakir": {
    "npc": "Dzakir (Agent-KA)",
    "text": "Kasus terakhir! Aku mengunduh logo perusahaan sepatu olahraga terkenal, lalu kucetak ke kaos kelas buatan kita sendiri untuk dijual di acara pensi. Boleh?",
    "options": [
      { "text": "Tentu boleh dong, hitung-hitung bantu promosi perusahaan sepatunya gratis.", "next": "q25_wrong", "score": 0 },
      { "text": "Tidak legal! Itu melanggar hak cipta dan merek dagang perusahaan tersebut.", "next": "q25_correct", "score": 4 }
    ]
  },
  "q25_wrong": {
    "npc": "Novita (KA)",
    "text": "Itu pemahaman yang fatal! Mengambil logo perusahaan terkenal dan menempelkannya di barang untuk dijual adalah tindakan yang sangat tidak legal[cite: 3].",
    "options": [
      { "text": "Wah, untung belum sempat kucetak. Mari lihat hasil akhirnya!", "next": "ending" }
    ]
  },
  "q25_correct": {
    "npc": "Novita (KA)",
    "text": "Selamat! Kesimpulanmu sangat tepat. Mengambil logo perusahaan untuk dijual kembali pada produk mandiri adalah hal yang ilegal[cite: 3].",
    "options": [
      { "text": "Selesai sudah semua tantangan! Mari lihat hasil predikatku!", "next": "ending" }
    ]
  }
}
berdasarkan 2 file html ini buatkan file Readme.md untuk github

Fail README.md anda telah sedia.
Ikon MD
 README 
MD

Dokumen ini direka khusus untuk repositori GitHub anda. Maklumat mengenai keterangan modul ("Petualangan Kreator Digital Beretika" dan "Arena Etika Digital"), panduan penggunaan luar talian, serta perincian pelesenan (MIT untuk kod sumber dan CC BY-NC 4.0 untuk kandungan pembelajaran) telah disatukan secara terperinci dan profesional di dalamnya. Anda boleh memuat naik fail ini secara terus ke repositori anda.

Konten yang Anda upload mungkin terlalu besar sehingga hasil tidak akan maksimal. Pelajari lebih lanjutTerbuka di jendela baru




Gemini adalah AI dan dapat melakukan kesalahan.

# Gamifikasi Pembelajaran KKA: Etika dan Hak Cipta

Proyek ini berisi kumpulan media pembelajaran interaktif berbasis gamifikasi untuk mata pelajaran **Koding dan Kecerdasan Artifisial (KKA)**, khusus untuk siswa Kelas 8. Materi difokuskan pada pemahaman **Etika Digital dan Hak Cipta**.

Media pembelajaran ini dirancang oleh **Yohan Adi Setiawan** untuk memfasilitasi pembelajaran yang menyenangkan dan interaktif, baik melalui pendekatan naratif (Visual Novel/RPG) maupun kompetitif (Arena Asesmen).

---

## 🎮 Daftar Permainan / Modul

Proyek ini terdiri dari dua file HTML utama yang dapat dijalankan secara langsung di peramban web (browser) tanpa memerlukan instalasi tambahan maupun koneksi internet (offline-ready).

### 1. Arena Etika Digital: Asesmen Awal untuk Etika dan Hak Cipta (`etikahakcipta.html`)
Sebuah permainan arena kompetitif yang dapat digunakan sebagai asesmen formatif atau sumatif.
- **Konsep:** Siswa menggerakkan avatarnya di dalam arena untuk memilih jawaban yang benar sebelum waktu habis.
- **Fitur:**
  - Papan skor *real-time*.
  - Soal berbasis waktu (Timer).
  - Antarmuka (UI) bernuansa *dark mode* modern dengan palet warna neon/pastel.

### 2. Petualangan Kreator Digital Beretika:Asesmen Pra Sumatif untuk Etika dan Hak Cipta (`rpg-etikahakcipta.html`)
Sebuah simulasi permainan peran (RPG) berbalut gaya Visual Novel. 
- **Konsep:** Siswa berperan sebagai Agen yang membantu karakter lain dalam memecahkan masalah terkait jejak digital, plagiarisme, atribusi, dan hak cipta.
- **Fitur:**
  - Narasi interaktif dengan percabangan pilihan.
  - Sistem poin (EXP) dan lencana (Badge) untuk melacak pemahaman siswa.
  - Penilaian berjenjang di akhir permainan (Unggul, Maju, Berkembang, Pra Berkembang).


---

## 🚀 Cara Penggunaan

1. **Unduh Repositori** ini ke perangkat komputer atau laptop Anda.
2. Buka salah satu file HTML (`rpg-etikahakcipta.html` atau `etikahakcipta.html`) menggunakan browser modern (Google Chrome, Microsoft Edge, Mozilla Firefox, atau Safari).
3. **Untuk Guru:** File ini dapat dibagikan kepada siswa secara langsung melalui grup kelas, Google Classroom, atau flashdisk. Karena menggunakan basis font dan styling internal, permainan dapat berjalan dengan lancar tanpa kuota internet.

---

## 🛠️ Modifikasi dan Pengembangan

- **Ubah Skenario / Soal:** Guru atau pengembang lain dapat memodifikasi narasi dan soal-soal di dalam file HTML secara langsung karena seluruh kode (HTML, CSS, JS) berada dalam satu berkas (Single-file deployment).
- **Tampilan UI/UX:** Tata letak antarmuka dirancang secara responsif menggunakan prinsip desain yang ramah pengguna. 

---

## 📄 Lisensi

Proyek ini menerapkan lisensi ganda:

1. **KODE SUMBER (HTML, CSS, JS)** berlisensi di bawah **MIT License**.
   *Izin diberikan secara gratis kepada siapa pun untuk menggunakan, menyalin, memodifikasi, dan mendistribusikan perangkat lunak ini.*
2. **KONTEN PEMBELAJARAN (Teks, Materi, Aset Media)** berlisensi di bawah **CC BY-NC 4.0** (Creative Commons Attribution-NonCommercial 4.0 International).
   *Anda bebas membagikan dan mengadaptasi materi ini selama memberikan atribusi (kredit) yang sesuai dan tidak digunakan untuk tujuan komersial.*

---

**© 2026 Yohan Adi Setiawan** *Membangun generasi kreator digital yang beretika, kritis, dan berdaya.*
README.md
Menampilkan README.md.
