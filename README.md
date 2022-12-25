# UASFakhriyAzkaFasya

# Ujian Akhir Semester 
<br>Mata Kuliah 	: DASAR PEMOGRAMAN
<br> Nama		: Fakhriy Azka Fasya
<br>NIM		:	1227050043
<br>Jurusan		:[Teknik Informatika](http://if.uinsgd.ac.id/) [UIN Sunan Gunung Djati Bandung](https://uinsgd.ac.id/) 

## Deskripsi Umum

Dalam Tugas Akhir Semester ini kita diberikan tugas untuk mengerjakan soal yang berhubungan dengan materi yang sudah kita pelajari selama belajar di matkul Dasar Pemograman. saat kita mengerjakan tugas yang diberikan, kodingan dibawah ini berfungsi untuk mencari nilai array dua dimensi dan metrix.

## Source Code

Soal No. 1
```cpp```

        #include<iostream>
        #include<iomanip>
        using namespace std;

        int main(){

          int arr[100][100], jumlahBaris, jumlahKolom, i, j, baris, kolom;

          cout<< "Tugas Program Mencetak Matrix Transpos\n";
          cout<< "=======================================\n";
          cout<< "Nama  : Fakhriy Azka Fasya\n";
          cout<< "Nim   : 1227050043\n";
            cout<< "                          \n";

            cout<<"Input jumlah baris: "; cin>>jumlahBaris;
            cout<<"Input jumlah kolom: "; cin>>jumlahKolom;
            cout << endl;

            for(i = 0; i < jumlahBaris; i++){
          for(j = 0; j < jumlahKolom; j++){
              cout << "Baris " <<i+1<<", kolom "<<j+1<< " = ";
              cin >> arr[i][j];
          }
          cout << endl;
            }
            cout << "Hasil matriks: " << endl;

            for(i = 0; i < jumlahBaris ; i++){
            for(j = 0; j < jumlahKolom; j++){
          cout << setw(3) << arr[i][j] << " ";
            }
            cout << endl;
            }

            baris = jumlahBaris;
            kolom = jumlahKolom;

            jumlahKolom = baris;
            jumlahBaris = kolom;

            cout << "\nUbah kolom jadi baris dan baris jadi kolom: " << endl;

            for(i = 0; i < jumlahBaris ; i++){
          for(j = 0; j < jumlahKolom; j++){
          cout << setw(3) << arr[j][i] << " ";
            }
            cout << endl;
            }
          return 0;
        }
        ```cpp```

Soal No. 2
```cpp```
        
        #include <iostream>
         #include <iomanip>
         using namespace std;
         int main(){

          int arr[100][100], jumlahBaris, jumlahKolom, i, j, baris, kolom;

          cout<< "Tugas Program Bilangan Yang Habis Dibagi 3,5,7\n";
          cout<< "==============================================\n";
          cout<< "Nama  : Fakhriy Azka Fasya\n";
          cout<< "Nim   : 1227050043\n";
          cout<< "                                               \n";

            cout<<"Input jumlah baris: "; cin>>jumlahBaris;
            cout<<"Input jumlah kolom: "; cin>>jumlahKolom;
            cout << endl;

            for(i = 0; i < jumlahBaris; i++){
          for(j = 0; j < jumlahKolom; j++){
              cout << "Baris " <<i+1<<", kolom "<<j+1<< " = ";
              cin >> arr[i][j];
          }
          cout << endl;
            }

            cout << "Hasil input nilai : " << endl;

            for(i = 0; i < jumlahBaris ; i++){
            for(j = 0; j < jumlahKolom; j++){
          cout << setw(3) << arr[i][j] << " ";
            }
            cout << endl;
            }

            cout << "\nHasil bilangan yang habis dibagi 3,5,7 : " << endl;

            for(i = 0; i < jumlahBaris ; i++){
            for(j = 0; j < jumlahKolom; j++){
          if(arr[i][j] % 3 == 0 || arr[i][j] % 5 == 0 || arr[i][j] % 7 == 0){
          cout << setw(3) << arr[i][j] << " ";
          }
            }
            cout << endl;
            }


            cout << endl;
            return 0;
        }
```cpp```

## Output
Nomor 1

![nomor 1](https://user-images.githubusercontent.com/121386988/209470765-418480ed-b3b0-4233-b563-29eb02b1c3e3.png)

Nomor 2

![nomor 2](https://user-images.githubusercontent.com/121386988/209470827-aa7b2f6f-2213-46da-8b07-a05950f400ab.png)

readme.md
Menampilkan readme.md.
