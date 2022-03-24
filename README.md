LAPORAN PRAKTIKUM
1. Membuat dokumen HTML
<img width="960" alt="membuat dokumen css" src="https://user-images.githubusercontent.com/101730390/159942767-5a4e6902-f66e-4d3d-8654-c4fed8d4fcb9.png">
HASIL CODINGAN
<img width="960" alt="hasil dokumen" src="https://user-images.githubusercontent.com/101730390/159942992-fa39906d-7b71-4d07-8f0c-f5d105e09c5e.png">

2. Mendeklarasikan CSS INTERNAL
<img width="960" alt="mendklarasikan css internal" src="https://user-images.githubusercontent.com/101730390/159943159-efb9fbbf-3e7d-4b70-90ff-834ac1afe6f8.png">
HASIL DEKLARASI CSS INTERNAL
<img width="960" alt="hasil deklarasi css internal" src="https://user-images.githubusercontent.com/101730390/159943228-91bbec50-b014-475a-866c-51bec0d20c44.png">

3. Menambahkan Inline CSS
<img width="960" alt="menambahkan inline css" src="https://user-images.githubusercontent.com/101730390/159943496-3df1b1ad-5c93-4c70-8869-38c9d4dd5695.png">
Hasil menambahkan inlen css
<img width="960" alt="hasil memabahkan inline css" src="https://user-images.githubusercontent.com/101730390/159943610-eb559ff6-7d99-4de7-aaa3-14ea34fc8ccf.png">

4. Membuat CSS Eksternal dan link
<img width="960" alt="membuat css eksternal" src="https://user-images.githubusercontent.com/101730390/159943924-8fd8fb4e-ec77-4703-ae91-f757515c9baa.png">
<img width="960" alt="menambahkan link style eksternal" src="https://user-images.githubusercontent.com/101730390/159944426-f70ea11f-7268-427a-ae0a-1f143f51a5e8.png">

Hasil membuat CSS eksternal dan link
<img width="960" alt="hasil menambahkan style eksternal dan link" src="https://user-images.githubusercontent.com/101730390/159944488-fd826386-241c-4a48-ae91-86cfa2d4af74.png">

5. Menambahkan CSS Selector
<img width="960" alt="membuat css selector" src="https://user-images.githubusercontent.com/101730390/159944672-fd098b76-7ca7-4518-ba59-438970cf4935.png">
Hasil menambahkan css selector
<img width="960" alt="hasil css selector" src="https://user-images.githubusercontent.com/101730390/159944827-947f1745-d748-4d5e-94f1-19b7c0ffb5f4.png">

SOAL!
1. Lakukan eksperimen dengan mengubah dan menambahkan properti dan nilai pada kode CSS dengan mengacu pada *CSS Cheat Sheet* yang diberikan pada file terpisan dari modul ini.
jawab : 
<img width="960" alt="coba eksperimen" src="https://user-images.githubusercontent.com/101730390/159958939-9fc1153b-91ed-4327-8378-0af5f52dc370.png">
<img width="960" alt="eksperimen" src="https://user-images.githubusercontent.com/101730390/159959002-5b4ac60d-2f7a-4d8d-b9dd-e3623a75d9d4.png">

2. Apa perbedaan pendeklarasian CSS elemen h1 {...} dengan #intro h1 {...}? jelaskan!
Jawab : 
h1{...} digunakan untuk memberikan style pada semua element h1 sedangkan #intro h1{..} digunakan untuk memberi style pada id selector dan bersifat kaku dan tidak bisa digunakan kembali pada elemen yang lainnya.

3. Apabila ada deklarasi CSS secara internal, lalu ditambahkan CSS eksternal dan inline CSS pada elemen yang sama. deklarasi manakah yang akan ditampilkan pada browser? jelaskan dan contohkan!
jawab :
Deklarasi utama yang akan ditampilkan adalah :
inline, internal, dan eksternal dan untukinnternal dan eksternal yang akan ditampilkan itu tergantung pada dimana yang terakhir diletakkan pada html. jika penggunaan inernal diatas eksternal maka link eksternal yang akan ditampilkan karena html akan memproses internal lalu eksternal yang mengakibatkan yang paling akhir yang akan ditampilkan/proses.

4. Pada sebuah elemen HTML, terdapat ID dan Class, apabila masing masing selector tersebut terdapat deklarasi css, maka deklarasi manakah yang akan ditampilkan pada browser? jelaskan dan beri contohnya! { <p id="paragraf-1" class="text-paragraf">}
jawab :
deklarasi id="paragraf-1" akan ditampilkan pada browser, karena selektor id lebih spesifik dari class atau bahkan elemen p itu sendiri, kecuali jika kita menambahkan property pada inline elemen p maka selektor id tersebut akan tertimpa, karena inline lebih spesifik daripada id, class dan elemen.
  deklarasi css selector
  <img width="960" alt="deklarasi css selector" src="https://user-images.githubusercontent.com/101730390/159951903-765c6a8d-b613-4f85-a389-8e76209fdc07.png">
  hasil deklarasi selektor
  <img width="960" alt="hasil deklarasi css selektor" src="https://user-images.githubusercontent.com/101730390/159952036-70d19323-62b5-413d-9e2d-bb7dce8b3ce8.png">

