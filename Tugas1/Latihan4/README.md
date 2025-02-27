```java

public class OperasiMatriks {
//menyatakakn kelas bernama OperasiMatriks

    public static void main(String[] args) {
    //menytakan main metode sebagai langkah awal mengeksekusi program


        // Program operasi matriks
        int[][] matriksA = {
            {1, 2, 3},
            {4, 5, 6}
        // Menyatakn dan menginisialisasi array dua dimensi matriks A dengan nilai awal pada Array 
        };

        int[][] matriksB = {
            {7, 8, 9},
            {10, 11, 12}
        //Menyatakkan dan menginisialisasi array dua dimensi matriksB dengan nilai awal pada Array 
        };

        // Penjumlahan matriks
        int[][] hasil = new int[2][3];
        //Meyatakakn array dua dimensi hasil yang akan digunakan  menyimpan hasil penjumlahan matriks A dan matriks B. Ukuran array nya sama dengan ukuran matriks A dan matriks B .


        for (int i = 0; i < matriksA.length; i++) {
            for (int j = 0; j < matriksA[0].length; j++) {
                hasil[i][j] = matriksA[i][j] + matriksB[i][j];
        // Loop for ini  untuk menelusuri setiap elemen dalam matriks A dan matriks B, Dan menjumlahkan elemen-elemen yang berkorespondensi, dan menyimpan hasil penjumlahan tersebut ke array hasil.
            }
        }

        // Menampilkan hasil
        System.out.println("Hasil penjumlahan matriks:");
        // menampilkan hasl Teks "hasil Penjumlahan matrikas" Di layar 

        for (int[] baris : hasil) {
            for (int nilai : baris) {
                System.out.print(nilai + " ");
            }
            System.out.println();
        //  for ini  untuk menelusuri setiap baris dalam array hasil, dan  mencetak setiap elemen dalam baris . Setelah mencetak elemen dalam satu baris, program mencetak baris baru dengan System.out.println().
        }
        }
    }
}

```