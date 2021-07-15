# Random-Forest-Classifier

Klasifikasi Random fores classifier yang di implementasikan secera sederhana menggu nakan python.
Liblary sklearn.ensemble di gunakan untuk mengimpor kleas RandomForestClassifier
kelas objek telah dibuat. Berikut nya di tersukan ke
objek :

- n_estimators = 10
 - criterion = 'entropy'

model awalh hanya kita berikan 10 pohon keputusan, yang akan menghasilkan 10prediksi yang salah.
Setelah model dilengkapi dengan lebih banyak pohon keputusan, jumlah prediksi yang salah semakin berkurang.

akan ditemukan bahwa jumlah pohon keputusan yang potimal untuk model seperti ini untuk meprediksi jawaban adalah 200 pohon keputusan
oleh karena itu arhumen n_estimator diberi nilai akhir 200.

dan lebih dari 200 akan menghasilkan over-=fitting dan akan menyuebabkan prediksi yang salah lebih lanjut
