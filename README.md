###Hasil dan flowchart
![pemrograman](https://user-images.githubusercontent.com/118960008/203720888-8cdc97d8-73aa-4226-b50b-8e83f6eef102.jpeg)
![TUGAS PEMROGRSMAN 9](https://user-images.githubusercontent.com/118960008/203720806-af8ae677-9c60-4e22-a526-8a12dd5e8f17.png)
###Penginputan
Nama = input("Masukkan Nama : ")

Nim = input("Masukkan NIM: ")

Matkul =input("Masukkan Mata Kuliah : ")

Absen = float(input("Masukkan Nilai Absensi : "))

Tugas =float(input("Masukkan Nilai Tugas: "))

UTS =float(input("Masukkan Nilai UTS: "))

UAS =float(input("Masukkan Nilai UAS: "))

R_Absen=int(Absen * 20/100)

R_Tugas=int(Tugas * 30/100)

R_UTS =int (UTS* 35/100)

R_UAS =int (UAS* 35/100)

nilai_akhir = R_Absen + R_Tugas + R_UTS + R_UAS

print("Nama : "+Nama)

print("Nim: "+Nim)

print("Matkul : "+Matkul)

print("Nilai Akhir: ", int(nilai_akhir))

if nilai_akhir >= 80:

print("Nilai: A")

elif nilai_akhir >=75:

print("Grade: B")

elif nilai_akhir >= 60:

print("Grade: C")

elif nilai_akhir >= 41:

print("Grade: D")

elif nilai_akhir >= 0:

print("Nilai: E")

if nilai_akhir >= 60:

print("Keterangan : LULUS")

else :

print ("Keterangan : TIDAK LULUS")


