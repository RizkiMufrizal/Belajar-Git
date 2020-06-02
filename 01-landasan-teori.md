#Bab 1 : Landasan Teori

##Version Control System (VCS)

Version Control System adalah sebuah sistem yang dapat mencatat setiap perubahan dari sebuah file dari waktu ke waktu. Dengan ada nya system tersebut mempermudah seseorang dalam mengembalikan perubahan - perubahan pada sebuah file. Beberapa contoh dari VCS adalah Git, Subversion (SVN), Mercurial dan lain - lain. Terdapat beberapa metode untuk VCS diantaranya adalah VCS Centralized dan VCS distributed

##VCS Centralized

Pada VCS ini terdapat sebuah server yang berfungsi sebagai pusat VCS server. Di dalam VCS server terdapat history penambahan, perubahan dan penghapusan dari file - file. Masing - masing developer sebelum melakukan perubahan terhadap file diwajibkan melakukan checkout terlebih dahulu agar file yang terdapat di local komputer untuk mendapatkan latest perubahan file. Proses melakukan checkout ini membutuhkan koneksi ke VCS server. Berikut adalah arsitektur dari VCS centralized.

![](./gambar/centralized.png)


##VCS Distributed

