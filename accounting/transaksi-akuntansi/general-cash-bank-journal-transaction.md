# General/Cash/Bank Journal Transaction

Secara umum penggunaan dari journal ini untuk setiap modul adalah sama namun yang membedakannya hanya ketika data disimpan dalam database.

* **General Journal** digunakan untuk transaksi – transaksi yang tidak mengunakan cash maupun bank. Dengan kata lain dalam journal tersebut tidak ada pembayaran maupun penerimaan uang.
* **Cash Journal** digunakan untuk transaksi yang melibatkan penggunaan uang cash.
* **Bank Journal** digunakan untuk transaksi yang melibatkan penggunaan uang bank.

<figure><img src="../../.gitbook/assets/list-journal.jpg" alt=""><figcaption><p>Tampilan list journal</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/form-journal.jpg" alt=""><figcaption><p>Tampilan form journal</p></figcaption></figure>

<table><thead><tr><th></th><th></th><th data-hidden></th></tr></thead><tbody><tr><td>No. Referensi</td><td>Nomor bukti / voucher</td><td></td></tr><tr><td>Tanggal Proses</td><td>Tanggal dimasukkan dalam journal</td><td></td></tr><tr><td>Tanggal Bukti</td><td>Tanggal Bukti voucher sebagai referensi transaksi</td><td></td></tr></tbody></table>

Untuk menginput data detail user harus menambah data data detail, sehingga akan tampil layar sebagai berikut :

<figure><img src="../../.gitbook/assets/detail-journal.jpg" alt=""><figcaption><p>Tampilan input detail journal</p></figcaption></figure>

|              |                                         |
| ------------ | --------------------------------------- |
| Departement  | Isi dengan kode departement             |
| Sub Code     | Sub code yang digunakan pada transaksi  |
| No. Account  | Nomor account                           |
| Uraian       | Keterangan dari transaksi               |
| Mata Uang    | Mata uang yang digunakan                |
| Nilai Tukar  | Nilai tukar pada saat terjadi transaksi |
| Debit,Credit | Jumlah nilai transaksi                  |

{% hint style="info" %}
&#x20;Untuk pengisian transaksi Cash maupun Bank Journal maka user hanya perlu menginput  journal  lawan  dari  bank  maupun  kas.  Sedangkan  untuk  General Journal, user wajib menginput journal debet maupun kreditnya.
{% endhint %}

Contoh kasus:

1. Transaksi Cash atau Bank Journal

<figure><img src="../../.gitbook/assets/transaksi-cash-atau-bank-journal.jpg" alt=""><figcaption></figcaption></figure>

Kemudian klik tombol simpan, setelah itu akan tampil layar sbb

<figure><img src="../../.gitbook/assets/simpan-journal.jpg" alt=""><figcaption></figcaption></figure>

Tekan tombol F2 untuk menyimpan transaksi maka layar selanjutnya
