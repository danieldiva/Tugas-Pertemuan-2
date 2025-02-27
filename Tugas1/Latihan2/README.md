```Penjelasan``
```java

public class PencarianArray {
// menyatakakn kelas bernama PencatianArray

    public static void main(String[] args) {
    // menytakan main metode sebagai langkah awal mengeksekusi program 


        // Program mencari nilai dalam array
        int[] nilai = {75, 80, 65, 90, 85, 70, 95, 88};
        // Menyatakan dan menginisialisasi array nilai dengan beberapa bilangan bulat.

        int cari = 90;
        //Menyatakan Nilai variabel yang berisi nilai yang akan dicari.

        boolean ketemu = false;
        // Menyatakan variabel jika  ketemu yang bertipe boolean, dandigunakan untuk menyimpan status apakah nilai yang dicari ditemukan atau tidak. dan akan lanjut di Inisialisasi dengan nilai false.

        int indeks = -1;
        //Mwnyatakan Variabel indeks yang di Gunakan


        // Mencari nilai
        for (int i = 0; i < nilai.length; i++) {
            if (nilai[i] == cari) {
                ketemu = true;
                indeks = i;
                break;
        // Menyatakan untuk mencari nilai cari dalam array .dan Loop ini menelusuri setiap elemen dalam array. Jika elemen yang sedang diperiksa sama dengan nilai yang akan dicari, variabel diubah menjadi true, indeks diisi dengan nilai i (indeks di mana nilai ditemukan), dan loop dihentikan dengan menggunakan break.
            }
            }
        }

        // Menampilkan hasil
        if (ketemu) {
            System.out.println("Nilai " + cari + " ditemukan pada indeks " + indeks);
        } else {
            System.out.println("Nilai " + cari + " tidak ditemukan");
        //Menyatakan hasil pencarian. Jika nilai yang dicari ditemukan (ketemu adalah true), maka program akan mencetak pesan bahwa nilai tersebut ditemukan pada indeks tertentu. Jika tidak ditemukan (ketemu adalah false), maka program akan mencetak pesan bahwa nilai tersebut tidak ditemukan.
        }
    }
}
```