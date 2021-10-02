# 01-git-github
Langkah Langkah Membuat Repo
    1. Instalasi Git
        - Pertama user harus download dan instal aplikasi git versi terbaru,
        - Sebelum menggunakan aplikasi Git, jangan lupa untuk download dan instal aplikasi text editor untuk menuliskan repo sebelum di sinkron ke Github, seperti VSCode,Notepatt,atau vim,
        - Setelah instalasi Git selesai, periksa dulu apakah aplikasi sudah terinstal di windows dengan mengecek pada Command prompt dengan menuliskan "git --version", ketika sudah terinstal dengan benar maka akan muncul versi Git yang di instal.
    2. Konfigurasi Git
        - Sebelum membuat repo maka user perlu membuat akun GitHub untuk menkonfigurasi aplikasi Git. 
        - Untuk sistem operasi Windows, konfigurasi ini akan disimpan di C:\Document and Settings\NamaUser dengan nama file .gitconfig. 
        - Gunakan perintah berikut pada "Git Cmd" :
        $ git config --global user.name "Nama Anda di GitHub"
        $ git config --global user.email emaildiGitHub@gmail.com
        - Lalu cek dengan perintah berikut :
        $ git config --list
    3. Mengelola atau Membuat repo
        - User membuka website GitHub pada browser dilaptop atau pc, kemudian pilih tana (+) pada pojok kanan atas sebelah gambar lonceng "New repository" untuk membuat repo baru, 
        - Ketikan nama projek, keterangan dan lisensi yang akan dibuat,
        - Klik pada "Create Repository"
        - User membuat file baru pada C/User/"nama project yang diGithub"
        - Untuk Clone repo pada file yang telah dibuat, user perlu klik kanan lalu pilih menu "git bash", ketikan perintah yang ada pada Github.
        - Barulah user menggunakan text editor untuk mengetikan projek repo yang akan dibuat.
