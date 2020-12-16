# Open Closed Principal
Memberikan gambaran yang jelas tentang apa yang di maksud dengan OCP. Setiap entitas software, baik itu (Class, module, fungsi) terbuka untuk perluasan, namun tertutup untuk modifikasi

# Tujuannya
Untuk menghindari keretakan software dikarenakan perubahan secara langsung terhadap sebuah class, module, ataupun function.

# Tentang Program
- Pada Source Code ini terdapat 2 program, yakni CouponWithOCP dan CouponWithoutOCP.
- Pada bagian CouponWithOCP, Kita dapat mengubah object menjadi object lain tanpa harus meninggalkan fungsi sesungguhnya dengan menggunakan Abstraction. Sedangkan pada bagian CouponWithoutOCP, jika kalian mengubah salah satu fungsi maka akan memengaruhi fungsi lain.