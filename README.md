# position-css
Position CSS 
basic task for MEA 

Position: Relative pada shape-layer
digunakan karena shape layer adalah layer parent dari circle dan box, jadi kita menempatkan element pada posisi yang sama seperti position static, tetapi karena menggunakan position relative kita juga bisa mengatur posisi element dengan menggunakan left, right, top & bottom.

Position: Absolute pada circle one, circle two, dan box.
digunakan karena kita ingin menempatkan element pada posisi/titik spesifik yang tidak dipengaruhi oleh elemen lain pada satu layout contohnya tidak dipengaruhi oleh document flow dan tidak mempengaruhi space. Absolute diatur oleh posisi left, right, top & bottom-nya untuk memudahkan shape circle & box menyatu dan berdekatan.

Hubungan position relative pada shape-layer dengan position absoulte pada circle dan box membuat titik posisi absolute circle & box akan dimulai dari posisi letak parentnya yaitu shape-layer. Jadi jika posisi left & top dari circle & box diset masing masing 0, maka posisi akan berada di atas kiri dari shape-layer


dalam task ini juga digunakan property rotate, untuk merotasi shape sesuai berdasarkan keinginan dalam satuan degrees (deg).