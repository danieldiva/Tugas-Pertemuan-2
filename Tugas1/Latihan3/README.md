```java

public class StatistikArray {
// menyatakakn kelas bernama StatistikArray 

    public static void main(String[] args) {
    // menytakan main metode sebagai langkah awal mengeksekusi program 


        // Program menghitung statistik nilai siswa
        int[] nilai = {75, 80, 65, 90, 85, 70, 95, 88};
          // Menyatakan dan menginisialisasi array nilai dengan beberapa bilangan bulat.

        // Mencari nilai tertinggi dan terendah
        int tertinggi = nilai[0];
        int terendah = nilai[0];
        int total = nilai[0];
        //Meyatakan variabel tertinggi, terendah, dan total. Variabel tertinggi dan terendah diinisialisasi dengan nilai elemen pertama dari array nilai. Variabel total juga diinisialisasi dengan nilai elemen pertama dari array nilai.

        for (int i = 1; i < nilai.length; i++) {
            if (nilai[i] > tertinggi) tertinggi = nilai[i];
            if (nilai[i] < terendah) terendah = nilai[i];
            total += nilai[i];
        // For Loop digunakan untuk mencari setiap elemen dalam array nilai mulai dari indeks 1 (elemen kedua) hingga elemen terakhir. Jika elemen saat ini (nilai[i]) lebih besar dari tertinggi, maka tertinggi diupdate dengan nilai tersebut. Jika elemen saat ini lebih kecil dari terendah, maka terendah diupdate dengan nilai tersebut. Setiap elemen juga ditambahkan ke variabel total.
        }

        double rataRata = (double) total / nilai.length;
        //Menghitung rata-rata nilai siswa dengan membagi total dengan array.dan hasil penghitungannya akan di Kalrifikasi untuk mendapatkan Nilai hasi; yang Lebih akurat

        System.out.println("Nilai tertinggi: " + tertinggi);
        System.out.println("Nilai terendah: " + terendah);
        System.out.println("Rata-rata: " + rataRata);
        // Menyatakn  nilai tertinggi, nilai terendah, dan rata-rata nilai siswa dan akan di tampilkan di layar .
    }
}

```