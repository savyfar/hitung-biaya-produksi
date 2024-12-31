#include <iostream>
using namespace std;

int main() {
    // Deklarasi variabel
    int jumlah_barang;
    float biaya_bahan_baku, biaya_tenaga_kerja, biaya_overhead, total_biaya;

    // Input jumlah barang dan biaya
    cout << "Masukkan jumlah barang yang diproduksi: ";
    cin >> jumlah_barang;

    cout << "Masukkan biaya bahan baku per unit (Rp): ";
    cin >> biaya_bahan_baku;

    cout << "Masukkan biaya tenaga kerja per unit (Rp): ";
    cin >> biaya_tenaga_kerja;

    cout << "Masukkan biaya overhead tetap (Rp): ";
    cin >> biaya_overhead;

    // Menghitung total biaya produksi
    total_biaya = (biaya_bahan_baku + biaya_tenaga_kerja) * jumlah_barang + biaya_overhead;

    // Menampilkan hasil
    cout << "Total biaya produksi adalah: Rp " << total_biaya << endl;

    return 0;
}
