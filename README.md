# terminal-customize
Repositori untuk terminal customize

## Install Oh My Posh
[on Windows](https://ohmyposh.dev/docs/installation/windows)

## Install Fonts `MesloLGM Nerd Font`
[how to installing fonts](https://ohmyposh.dev/docs/installation/fonts)

#### Link [setup config list](./how%20to%20setup%20config.txt)
#### These are my custom theme configurations for Oh My Posh., [aliens.omp.json](./aliens.omp.json)

### for PowerShell OR WindowsPowershell
1. Buka terminal PowerShell atau WindowsPowershell
```sh 
NOTEPAD $PROFILE
```
2. Copy paste kode berikut:
Jika PowerShell
```sh
oh-my-posh init pwsh --config 'C:\Users\acer\Documents\PowerShell\aliens.omp.json' | Invoke-Expression
```
Jika WindowsPowerShell
```sh
oh-my-posh init pwsh --config 'C:\Users\acer\Documents\WindowsPowerShell\aliens.omp.json' | Invoke-Expression
```

### for CMD (Command Prompt) , run `clink info` inside cmd to find that file's location.
1. Download [clink](https://chrisant996.github.io/clink/)
2. Cek Version
```sh
clink --version
```
3. Cari lokasi di `script` belakang
```sh
clink info
```

### for Git Bash
1. Cek Apakah File `.bashrc` Sudah Ada
Buka Git Bash.
Jalankan perintah berikut untuk memeriksa keberadaan file:
```sh
ls -a ~/.bashrc
```
Jika file .bashrc tidak muncul dalam daftar, lanjutkan ke langkah berikut untuk membuatnya.
2. Membuat File `.bashrc`
Gunakan editor teks seperti nano untuk membuat file .bashrc:
```sh
nano ~/.bashrc
```
Tambahkan konfigurasi yang diperlukan, seperti:
```sh
eval "$(oh-my-posh init bash)"
```
Simpan dan keluar dari editor:
    - Tekan `CTRL + O` untuk menyimpan.
    - Tekan `CTRL + X` untuk keluar.
3. Reload File `.bashrc`
Setelah membuat atau mengedit file `.bashrc`, jalankan perintah berikut agar perubahan diterapkan tanpa perlu me-restart terminal:
```sh
source ~/.bashrc
```
atau
```sh
. ~/.bashrc
```

## Need a Customize
[How to customizations](https://ohmyposh.dev/docs/installation/customize)