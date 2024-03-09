# <h1 align="center">Laporan Praktikum Modul Tipe Data</h1>
<p align="center">Muhammad Iqbal</p>
<p align="center">2311110013</p>

## Dasar Teori

Tipe data adalah klasifikasi nilai yang digunakan dalam pemrograman untuk menentukan jenis operasi yang dapat dilakukan terhadap data tersebut dan cara data tersebut disimpan dalam memori komputer. Tipe data memungkinkan kompiler atau interpreter untuk memahami bagaimana data akan digunakan oleh program.

## Guided 

### 1. Tipe Data Primitif

```C++
#include <iostream>
using namespace std;

int main()
{
    char op;
    float num1, num2;
    // It allows user to enter operator i.e. +, -, *, /
    cin >> op;
    // It allow user to enter the operands
    cin >> num1 >> num2;
    // Switch statement begins
    switch (op)
    {
    // If user enter +
    case '+':
        cout << num1 + num2;
        break;
    // If user enter -
    case '-':
        cout << num1 - num2;
        break;
    // If user enter *
    case '*':
        cout << num1 * num2;
        break;
    // If user enter /
    case '/':
        cout << num1 / num2;
        break;
    // If the operator is other than +, -, * or /,
    // error message will display
    default:
        cout << "Error! operator is not correct";
    } // switch statement ends
    return 0;
}

```
Tipe data primitif adalah tipe data yang sudah ditentukan oleh sistem dan disediakan oleh banyak bahasa pemrograman. Perbedaan antara tipe data primitif terletak pada jumlah bit yang dialokasikan untuk setiap tipe data primitif, yang tergantung pada bahasa pemrograman, kompiler, dan sistem operasi yang digunakan. Contoh tipe data primitif termasuk int, float, char, dan boolean.

Tipe data primitif seperti int digunakan untuk menyimpan bilangan bulat seperti 12, 1, 4, dan sebagainya. float digunakan untuk menyimpan bilangan desimal seperti 1.5, 2.1, 3.14, dan sebagainya. char berfungsi untuk menyimpan data berupa huruf atau simbol seperti A, B, C, dan seterusnya. Sedangkan boolean digunakan untuk menyimpan nilai boolean yang hanya memiliki dua nilai yaitu true dan false.


### 2. Tipe Data Abstrak

```C++
#include <stdio.h>

//Struct
struct Mahasiswa
{
    const char *name;
    const char *address;
    int age;
};

int main()
{
    // menggunakan struct
    struct Mahasiswa mhs1, mhs2;
    // mengisi nilai ke struct
    mhs1.name = "Dian";
    mhs1.address = "Mataram";
    mhs1.age = 22;
    mhs2.name = "Bambang";
    mhs2.address = "Surabaya";
    mhs2.age = 23;

    // mencetak isi struct
    printf("## Mahasiswa 1 ##\n");
    printf("Nama: %s\n", mhs1.name);
    printf("Alamat: %s\n", mhs1.address);
    printf("Umur: %d\n", mhs1.age);
    printf("## Mahasiswa 2 ##\n");
    printf("Nama: %s\n", mhs2.name);
    printf("Alamat: %s\n", mhs2.address);
    printf("Umur: %d\n", mhs2.age);
    return 0;
}

```


## Unguided 

### 1. [Soal]

```C++
#include <iostream>
using namespace std;

int main() {
    cout << "ini adalah file code unguided praktikan" << endl;
    return 0;
}
```
#### Output:
![240302_00h00m06s_screenshot](https://github.com/suxeno/Struktur-Data-Assignment/assets/111122086/6d1727a8-fb77-4ecf-81ff-5de9386686b7)

Kode di atas digunakan untuk mencetak teks "ini adalah file code guided praktikan" ke layar menggunakan function cout untuk mengeksekusi nya.

#### Full code Screenshot:
![240309_10h21m35s_screenshot](https://github.com/suxeno/Struktur-Data-Assignment/assets/111122086/41e9641c-ad4e-4e50-9ca4-a0215e336b04)


## Kesimpulan
Ringkasan dan interpretasi pandangan kalia dari hasil praktikum dan pembelajaran yang didapat[1].

## Referensi
[1] I. Holm, Narrator, and J. Fullerton-Smith, Producer, How to Build a Human [DVD]. London: BBC; 2002.