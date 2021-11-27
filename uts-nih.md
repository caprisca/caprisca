1. Download ISO Installer windows server 2022. Link download tersedia pada e-learning
2. Jika sudah di download, buka virtual box klik machine lalu pilih new dan beri nama. Seperti gambar dibawah ini :
![1](uts/1.PNG)
![1](uts/2.PNG)
3. Pilih seberapa besar kamu ingin menggunakan storage dan tipe mana yang diinginkan
![1](uts/3.PNG)
![1](uts/4.PNG)
![1](uts/5.PNG)
![1](uts/6.PNG)
![1](uts/7.PNG)
4. Selanjutnya, pilih machine klik “Network” lalu atur menjadi “Bridge adapter” lalu ok
![1](uts/8.PNG)
5. klik Start
![1](uts/9.PNG)
6. klik “Start” lalu Windows Server 2022 installation wizard akan loading dan install
![1](uts/10.PNG)
![1](uts/11.PNG)
![1](uts/12.PNG)
7. Pilih lisensi
![1](uts/13.PNG)
![1](uts/14.PNG)
![1](uts/15.PNG)
![1](uts/16.PNG)
8. Lalu windows server akan kembali loading
![1](uts/17.PNG)
9. Atur password, dan masukan Password yang telah diatur tadi
![1](uts/18.PNG)
![1](uts/19.PNG)
10. Pilih menu “Devices – Insert Guest Additions CD Image” lalu ikuti alurnya
 ![1](uts/20.PNG)
 ![1](uts/21.PNG)
 ![1](uts/22.PNG)
 ![1](uts/23.PNG)
 ![1](uts/24.PNG)
11. Masukkan password lagi
 ![1](uts/25.PNG)

Instalasi Active Directory Domain Services
1. Lakukan rename terlebih daahulu “rename-computer -Newname Catharina”
 ![1](uts/26.PNG)
2. Pilih menu “Server Manager”. Lalu pilih opsi “Manage" dan “Add Roles and Features”. Kemudian klik “Next”.
  ![1](uts/27PNG)
3. Pilih opsi “Role-based or feature-based installation”. dan “Next”
   ![1](uts/28PNG)
4. Klik “Select a server from the server pool” untuk memilih direktori penyimpanan lokal. Lalu “Next”
   ![1](uts/29PNG)
5. Klik tanda centang di kotak “Active Directory Domain Services”. lalu "add features"
   ![1](uts/30PNG)
6.Klik centang kotak “Group Policy Management” lalu “Next”.
   ![1](uts/31PNG)
   ![1](uts/32PNG)


Instalasi DNS Server
1. Pilih menu “Server Manager”. Lalu pilih opsi “Manage" dan “Add Roles and Features”. Kemudian klik “Next”.
   Dan centang kotak pada DNS Server
   ![1](uts/33PNG)
2. Kemudian Centang “.NET Framework 3.5 features”
   ![1](uts/34PNG)
3. Pilih Install dan tunggu hingga selesai
   ![1](uts/35PNG)
   ![1](uts/36PNG)
   
   
Promote Server to a Domain Controller
1. Lakukan Konfigurasi AADS
   ![1](uts/37PNG)
   ![1](uts/38PNG)
   ![1](uts/39PNG)
 2. Buka Ethernet Properties daan atur seperti dibawah ini :
   ![1](uts/40PNG)
 3. Buka Notifikasinya
   ![1](uts/41PNG)
 4. Klik “Add a new forest” dan masukkan nama domain yang akan digunakan pada Root Domain Name
   ![1](uts/42PNG)
 5. Klik “Windows Server 2016” pada functional level, dan centang “Domain Name System (DNS) server” dan ”Global Catalog"
    Lalu atur Password
    ![1](uts/43PNG)
 6. Isi nama “The NetBIOS domain name” sesuai dengan nama domain
    ![1](uts/44PNG)
 7. Pilih Next
    ![1](uts/45PNG)
 8. Dan.... Berakhir di step ini, karena punya saya error
    ![1](uts/46PNG)
    
    
 Terima Kaish telah membuka dan membaca page ini sampai selesai. Jika ada kesalahan dan ketidak tepatan 
 dalam hal waktu pengumpulan, ssaya ucapkan Mohon Maaf :)
