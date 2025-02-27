```Penjelasan``
```java

public class LatihanArray1 {
    // Menyatakan kelas bernama LatihanArray1

    public static void main(String[] args) {
       // menytakan main metode sebagai langkah awal mengeksekusi program 

        int[] bilanganGenap = new int[10];
        // Menyatakan sebuah array yang isinya 10 elemen bilangan bulat

        int jumlah = 0;
        // Menyatakan sebuah variabel jumlah dan menginisialisasinya dengan nilai 0.

        // Mengisi array
        for (int i = 0; i < bilanganGenap.length; i++) {
            bilanganGenap[i] = (i + 1) * 2;
        // Mengisi setiap Array bilangan genap dengan bilangan genap,  Dan akan Menelusuri setiap indeks array dan mengisi setiap elemen dengan bilangan genap.
        }
        }

        // Menampilkan array
        System.out.println("Isi array:");
        // mencetak teks isi array ke layar

        for (int bilangan : bilanganGenap) {
            System.out.print(bilangan + " ");
            jumlah += bilangan;
        // Menelusuri setiap elemen array Bilangan genap,mencetak elemen  ke layar, dan menambahkan nilai elemen ke variabel jumlah.

        }

        System.out.println("\\nJumlah semua elemen: " + jumlah);
        // Mencetak semua elemen array Bilangan genap ke Layar .
    }
}

```
