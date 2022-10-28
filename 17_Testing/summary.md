# React Testing Library adalah seperangkat helpers yang memungkinkan Anda mengetes komponen pada React tanpa bergantung pada detail implementasinya. Pendekatan ini membuat refactoring menjadi mudah dan juga mendorong Anda untuk menerapkan best practices untuk aksesbilitas.
# Jest adalah test runner pada JavaScript yang memungkinkan Anda mengakses DOM melalui jsdom. Sementara jsdom hanyalah perkiraan cara kerja browser, seringkali cukup baik mengetes komponen pada React. Jest memberikan kecepatan iterasi yang bagus dikombinasikan dengan fitur-fitur yang powerful seperti mocking modules dan timers sehingga Anda dapat memiliki kontrol lebih pada kode yang dijalankan.
# Ada beberapa cara untuk mengeteskomponen pada React. Secara umum, terbagi menjadi dua kategori:1. Rendering component trees di dalam environment tes yang sudah disederhanakan dan ditegaskan pada keluarannya. 2. Menjalankan aplikasi lengkap di dalam environment peramban asli (juga dikenal sebagai tes “end-to-end”).