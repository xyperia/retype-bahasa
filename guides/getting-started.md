---
order: 100
icon: rocket
tags: [guide]
---
Simulasi Retype dapat dilakukan hanya bila Retype sudah diinstal menggunakan [npm](https://www.npmjs.com/get-npm), [Yarn](https://classic.yarnpkg.com/en/docs/install/), atau [dotnet](https://dotnet.microsoft.com/download/dotnet-core) CLI.

Berikut cara yang dilakukan untuk menginstall Retype
+++ NPM
```
npm install retypeapp --global
```
+++ Yarn
```
yarn global add retypeapp
```
+++ dotnet
```
dotnet tool install retypeapp --global
```
+++

Untuk membuat proyek dokumentasi Retype baru, teman-teman cukup buat folder baru lalu akses folder tersebut dari Terminal / Command Prompt.

Selanjutnya teman-teman cukup menjalankan perintah `retype watch`

Voila! Teman-teman sudah berhasil menjalankan Retype di perangkat masing-masing.

---

## Live reload

Retype akan secara otomatis mendeteksi perubahan yang dilakukan di direktori tempat Retype dijalankan dan perubahan akan langsung bisa dilihat di browser teman-teman.

Perintah `retype watch` akan menjalankan ketiga perintah dibawah.

```
retype init
retype build
retype run
```

---

## Uninstall

Uninstalasi Retype dapat dilakukan dengan perintah berikut. Namun perlu diingat bahwa uninstalasi Retype dapat dilakukan dengan package manager yang digunakan saat instalasi. Misalnya teman-teman menggunakan `npm` saat instalasi, uninstalasi hanya dapat dilakukan menggunakan perintah untuk `npm` juga.

+++ npm
```
npm uninstall retypeapp --global
```
+++ yarn
```
yarn global remove retypeapp
```
+++ dotnet
```
dotnet tool uninstall retypeapp --global
```
+++

Setelah uninstalasi berhasil dilakukan, file yang berkaitan dengan Retype seperti `retype.yml` dan folder `.retype` akan dihapus.