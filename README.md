## filmfinder

**Version 1.0.0**</br>
untuk melakukan pencarian film sederhana
>https://dendi6.github.io/filmfinder/

---
## download
untuk memulai projek lakukan clone. dengan cara
>git clone https://github.com/dendi6/filmfinder.git

## memulai
saat projeck sudah di clone lakukan instalasi npm dengan cara
>npm install

## Menjalankan
Menjalankan projeck dapat dilakukan dengan 2 cara
>npm run build</br>
>npm run start-dev

## push ke github
untuk melakukan push ke github dapat di lakukan dengan cara
1. >git add .
2. >git commit -m "isi pesan"
3. >git push origin master

## Menggunakan Github Pages
Menggunakan github pages.
>npm install gh-pages

saat paket sudah selesai tambahkan homepage di berkas <b>package.json</b>
>"homepage" : "https://namagithub.github.io/namarepisitori/"

masih pada <b>package.json</b> tambahkan kata seperti ini di bagian script
>"predeploy" : "npm run build",</br>
>"deploy" : "gh-pages -d dist"

langkah terakhir dapat dilakukan dengan perintah
>npm run deploy

## Kesahalah push
Seperti yang dinyatakan dalam pesan Kesalahan, Anda harus "mengambil dulu". Ini berhasil untuk saya. Gunakan perintah:
>git fetch origin master

Kemudian ikuti langkah-langkah berikut untuk menggabungkan:
>git pull origin master
>git add .
>git commit -m 'your commit message'
>git push origin master

---
## Contributor
- Dendi

---
## copyright
© Dendi,
