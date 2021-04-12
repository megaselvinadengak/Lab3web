# Lab3web


# Nama  : Mega S Dengak
# Nim   : 311910130
# Kelas : TI.19.A.1
#

# Praktikum 3: Membuat List, Table dan Form


# List
HTML List memungkinkan untuk mengelompokkan sekumpulan item terkait dalam sebuah daftar. 
HTML sudah menyediakan elemen untuk membuat list. Ada tiga macam jenis list yang bisa dibuat 
di HTML, yaitu:
• Ordered List adalah list yang terurut;
• Unordered List adalah list yang tak terurut;
• dan Descriptiona List adalah list yang berisi definisi.


# Ordered List
Digunakan untuk membuat daftar dimana tiap bagiannya ditandai dengan sebuah simbol. Ordered 
list dibuat dengan tag < ol >. Lalu di dalamnya diisi dengan item-item yang akan dimasukkan ke 
dalam list. Item dibuat dengan tag < li > (list item).

# Membuat Ordered List
![Membuat Unorderd List](https://user-images.githubusercontent.com/56498195/114265143-6f791c00-9a19-11eb-95cf-1efd7007dbc9.PNG)

#
![Membuat Ordered List 2](https://user-images.githubusercontent.com/56498195/114265150-7869ed80-9a19-11eb-8717-b8986d8e8481.PNG)

# Membuat Unorderd List
Digunakan untuk membuat daftar dimana tiap bagiannya memiliki nomor secara terurut.
Unordered list dibuat dengan tag < ul > dan untuk item-nya dibuat juga dengan tag < li >.

Secara default simbol yang digunakan oleh unordered list adalah lingkaran kecil (disc). Simbol tersebut dapat diubah sesuai dengan kebutuhannya, seperti kotak, lingkaran, atau tanpa simbol. Untuk mengubahnya dengan menambahkan atribut type pada tag ul dan berikan nilainya sesuai dengan yang diinginkan.
• square untuk simbol persegi;
• disc (default) untuk simbol lingkaran disc;
• none tidak memakai simbol;
• circle untuk simbol lingkaran;
Selain menggunakan atribut type, dapat juga diubah dengan nilai lainnya menggunakan gambar atau icon. Untuk merubahnya menggunakan CSS dengan property list-style-image. 

![Membuat Unorderd List](https://user-images.githubusercontent.com/56498195/114265143-6f791c00-9a19-11eb-95cf-1efd7007dbc9.PNG)

#
![Membuat Unorderd List 2](https://user-images.githubusercontent.com/56498195/114265231-dd254800-9a19-11eb-850d-ee270a0f35de.PNG)


# Membuat Description List
Digunakan untuk membuat daftar dimana tiap daftar tersebut memiliki penjelasan (sub-bagian).
Ada tiga tag yang digunakan untuk membuat description list, yaitu:
• < dl > (description list) tag untuk memulai description list;
• < dt > (description term) tag untuk membuat kata yang akan dideskripsikan;
• < dd > (description description) tag untuk membuat penjelasan dari kata.
  
![Membuat Description List](https://user-images.githubusercontent.com/56498195/114265250-faf2ad00-9a19-11eb-829f-a081406be28a.PNG)

#
![Membuat Description List 2](https://user-images.githubusercontent.com/56498195/114265258-0514ab80-9a1a-11eb-9ae0-825ee7906e2e.PNG)


# Membuat Tabel
Digunakan untuk menyajikan data dalam bentuk kolom dan baris, tujuannya agar informasi dapat 
ditampilkan secara lebih terstruktur dan tabular.

![membuat tabel](https://user-images.githubusercontent.com/56498195/114265298-3e4d1b80-9a1a-11eb-90b3-417da9fb979f.PNG)

#
![membuat table](https://user-images.githubusercontent.com/56498195/114265327-68064280-9a1a-11eb-9760-1e8d7b17ef3b.PNG)


# Menggabungkan Sel Data
Sel data pada tabel dapat digambugkan untuk keperluan tertentu. Untuk menggabungkan sel secara vertikal menggunakan atribut rowspan dan untuk menggabungkan sel secara horizontal menggunakan atribut colspan. Atribut tersebut dapat ditambahkan pada tag td (tabel data) dengan nilai atributnya adalah jumlah sel yang akan digabungkan. 

![Menggabungkan Sel Data](https://user-images.githubusercontent.com/56498195/114265360-8ec47900-9a1a-11eb-8ce6-1f9498e92042.PNG)

#
![Menggabungkan Sel Data 2](https://user-images.githubusercontent.com/56498195/114265355-89ffc500-9a1a-11eb-8004-7bdcaab7182a.PNG)


# Membuat Form
Form
Web tidak hanya berfungsi untuk menampilkan informasi, namun dapat juga menerima data dari 
pengunjungnya. Salah satu cara untuk mengambil data dari pengunjung adalah dengan 
menggunakan form. Form pada web berlaku sama halnya dengan formulir di dunia nyata. Form 
dapat diisi kemudian diproses dengan program tertentu, baik dari sisi server ataupun dari sisi 
client.

Untuk membuat form digunakan tag <form> dengan atribut action dan method. Atribut action
untuk menentukan aksi yang akan digunakan pada saat form dikirim. Dan method adalah untuk 
menentukan metode yang digunakan dalam mengirimkan data.
  
• Atribut action dapat diisi dengan url endpoint yang akan memproses data.
• Atribut enctype: Mendefinsikan cara encoding data sebelum dikirimkan. Biasanya digunakan jika ingin meng-upload file.
• Atribut method: Metode pengiriman data.
o GET: Data dikirimkan bersama URL.
o POST: Data dikirimkan terpisah dari URL


![Membuat Form](https://user-images.githubusercontent.com/56498195/114265392-c29f9e80-9a1a-11eb-946a-0cf0f50618e7.PNG)

#
![mwmbuat form](https://user-images.githubusercontent.com/56498195/114265394-c4696200-9a1a-11eb-8cfa-b5e860888034.PNG)

#
![membuat form 2](https://user-images.githubusercontent.com/56498195/114265423-e367f400-9a1a-11eb-8964-b1cdfbb9e250.PNG)

#
![Menabahkan Style pada Form 2](https://user-images.githubusercontent.com/56498195/114265431-efec4c80-9a1a-11eb-8273-9eeaade399ac.PNG)


# Pertanyaan dan Tugas
1. Buatlah form yang menampilkan dropdown menu dan listbox dengan multiple selection.


# Dropdown Menu
![dropdown 1](https://user-images.githubusercontent.com/56498195/114411970-e4458500-9bd6-11eb-9cf3-cf5e79a27db8.PNG)

#
![dropdown 2](https://user-images.githubusercontent.com/56498195/114411994-e90a3900-9bd6-11eb-8701-5b77dc95c27f.PNG)

#
![dropdown 3](https://user-images.githubusercontent.com/56498195/114412001-ea3b6600-9bd6-11eb-90ca-23f40d45ddf2.PNG)



# Listbox
![listbox 2](https://user-images.githubusercontent.com/56498195/114412153-08a16180-9bd7-11eb-868d-2f35646eac8d.PNG)

#
![listbox1](https://user-images.githubusercontent.com/56498195/114412197-122ac980-9bd7-11eb-909e-261d8665bd76.PNG)











