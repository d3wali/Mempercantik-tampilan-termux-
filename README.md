# Mempercantik-tampilan-termux-
# Tutorial Mempercantik Tampilan Termux

Termux adalah terminal emulator yang memungkinkan kamu menjalankan Linux di perangkat Android. Dengan beberapa penyesuaian, kamu bisa membuat tampilan Termux lebih menarik dan nyaman untuk digunakan. Berikut adalah beberapa langkah untuk mempercantik tampilan Termux.

## 1. **Mengubah Warna dan Tema**

Termux memungkinkan kita untuk mengubah warna dan tema untuk tampilan yang lebih menarik. Ikuti langkah-langkah berikut:

### **Instalasi Paket Termux-API**
```bash
pkg update && pkg upgrade
pkg install termux-api

mengubah tema

pkg install termux-style
termux-style -h

termux-style -i 2

pkg install zsh
chsh -s zsh

pkg install git
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"

pkg install neofetch

neofetch

pkg install fontconfig
curl -fLo ~/.termux/fonts/nerd-fonts.zip https://github.com/ryanoasis/nerd-fonts/releases/download/v2.1.0/UbuntuMono.zip
unzip ~/.termux/fonts/nerd-fonts.zip -d ~/.termux/fonts/

