SOAL1
public class HotelAmaris {
    public static void main(String[] args) {

        // Deklarasi array dua dimensi (4 lantai x 5 kamar)
        char[][] hotel = {
            {'', '', '', 'X', ''}, // Lantai 4
            {'', '', '', '', '*'}, // Lantai 3
            {'', '', '', '', '*'}, // Lantai 2
            {'', '', '', '', 'X'}  // Lantai 1
        };

        // Menampilkan posisi tamu (nilai 'X')
        System.out.println("=== Keberadaan Tamu di Hotel Amaris ===");
        for (int i = 0; i < hotel.length; i++) {
            for (int j = 0; j < hotel[i].length; j++) {
                if (hotel[i][j] == 'X') {
                    int lantai = 4 - i;     // konversi baris menjadi lantai
                    int kamar = j + 1;      // konversi kolom menjadi nomor kamar
                    System.out.println("Tamu berada di Lantai " + lantai + " Kamar " + kamar);
                }
            }
        }
    }
}

Soal2
public class JumlahKamarKosong {
    public static void main(String[] args) {

        // Array hotel sama seperti soal pertama
        char[][] hotel = {
            {'', '', '', 'X', ''}, // Lantai 4
            {'', '', '', '', '*'}, // Lantai 3
            {'', '', '', '', '*'}, // Lantai 2
            {'', '', '', '', 'X'}  // Lantai 1
        };

        int kosong = 0; // variabel penghitung kamar kosong

        // Perulangan untuk menghitung jumlah '*'
        for (int i = 0; i < hotel.length; i++) {
            for (int j = 0; j < hotel[i].length; j++) {
                if (hotel[i][j] == '*') {
                    kosong++;
                }
            }
        }

        // Menampilkan hasil
        System.out.println("Jumlah kamar yang tersedia adalah " + kosong + " kamar");
    }
}
