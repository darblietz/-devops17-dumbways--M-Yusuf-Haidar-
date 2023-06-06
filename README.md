# Task Introduction to DevOps
### 1.Definisi DevOps

DevOps adalah penghubung tim development & operations, yang bertugas
 untuk mempercepat proses development hingga rilis produk ke publik.


### 2.Sebutkan Lifecycle DevOps dan Jelaskan definisi-definisinya! 

- Continuous Deployment atau Continuous Delivery (CD) adalah praktek pengiriman perangkat lunak ke lingkungan produksi secara otomatis setelah melalui tahap integrasi, pengujian, dan verifikasi.
- Continuous Integration (CI) adalah pengintegrasian kode ke dalam repositori kode kemudian menjalankan pengujian secara otomatis, cepat, dan sering.

- Continuous Testing adalah pengujian perangkat lunak dan mencari issue selama fase ini. Jika terjadi bug atau kesalahan, kode dikembalikan ke fase integrasi untuk diperbaiki. Selain itu, pengujian otomasi meminimalkan waktu dan upaya yang diperlukan untuk mendapatkan temuan yang andal. Selama tahap ini, tim menggunakan teknologi seperti Selenium. Selain itu, pengujian berkelanjutan meningkatkan laporan penilaian pengujian dan mengurangi biaya pengiriman dan pemeliharaan lingkungan pengujian.
- Continuous Deployment adalah Ini adalah langkah paling penting dan aktif dari siklus hidup DevOps, di mana kode yang sudah selesai dirilis ke server produksi. Penyebaran berkelanjutan melibatkan manajemen konfigurasi untuk memastikan penyebaran kode yang tepat dan lancar di server. Sepanjang fase produksi, tim pengembangan mengirimkan kode ke server dan menjadwalkan pemutakhiran server, mempertahankan konfigurasi yang konsisten. 


- Continuous Feedback adalah Umpan balik diterapkan untuk menilai dan meningkatkan kode sumber aplikasi. Selama fase ini, perilaku klien diperiksa secara rutin untuk setiap rilis dalam upaya meningkatkan rilis dan penerapan di masa mendatang. Perusahaan dapat mengumpulkan umpan balik menggunakan strategi terstruktur atau tidak terstruktur.
Di bawah metode struktural, masukan dikumpulkan dengan menggunakan kuesioner dan survei. Sebaliknya, umpan balik diterima dengan cara yang tidak terstruktur melalui platform media sosial. Fase ini sangat penting untuk memungkinkan pengiriman berkelanjutan guna merilis versi program yang lebih baik.

- Continuous Monitoring adalah proses dan teknologi yang digunakan untuk mendeteksi kepatuhan dan masalah risiko yang terkait dengan lingkungan keuangan dan operasional organisasi.

- Continuous Operations adalah Fase terakhir siklus hidup DevOps sangat penting untuk meminimalkan pemeliharaan terjadwal dan waktu henti terencana lainnya. Biasanya, pengembang terpaksa membuat server offline untuk melakukan pembaruan, yang meningkatkan waktu henti dan dapat menghabiskan banyak uang bagi organisasi. Akhirnya, operasi berkelanjutan mengotomatiskan startup aplikasi dan peningkatan berikutnya. Ini menghilangkan downtime menggunakan platform manajemen kontainer seperti Kubernetes dan Docker.


### 3. Installasi Ubuntu Server menggunakan VMWare.

  #### 1.Klik aplikasi VMWare, dan pilih "Create a New Virtual Machine"
  ![1](https://github.com/darblietz/Introduction-to-DevOps/assets/98991080/41715a68-44fa-4184-9446-ceacd6ae5557)

  #### 2. Klik Browse untuk memilih file VMWare berupa .iso. dan Setelah Ubuntu ter-detected. Maka klik Next.
  ![2](https://github.com/darblietz/Introduction-to-DevOps/assets/98991080/6c4779da-1a9c-4362-b082-ba1f2b4e3a55)
  
  #### 3. Silahkan isi data yang kalian inginkan, random juga tidak apa-apa.
  ![3](https://github.com/darblietz/Introduction-to-DevOps/assets/98991080/c1108707-33e0-40a4-91a0-7b9a3f0caa77)
  
  #### 4. Namakan Virtual machine, random. dan ada location penyimpanan folder untuk server anda juga. Setelah selesai, Klik Next
  ![4](https://github.com/darblietz/Introduction-to-DevOps/assets/98991080/2f74ef19-936e-48dc-95c1-da2931063fed)

  #### 5. Kita ubah ukuran maksimum disknya menjadi 10 Gb. dan pilih opsi "Split virtual disk into multiple files", fungsinya untuk apabila kita ingin memindahkan ke device lain, akan lebih mudah dan cepat tranfernya data.
 ![5](https://github.com/darblietz/Introduction-to-DevOps/assets/98991080/fc7ac3a3-68ae-4764-8cff-1bf8e09d7525)
 
  #### 6.Klik "Custumize Hardware", untuk mengganti beberapa fitur.
  ![6](https://github.com/darblietz/Introduction-to-DevOps/assets/98991080/f0d44817-eab3-406e-ac40-67e2c273855d)
  
  #### 7. Kita ubah Spesifikasi untuk jumlah memory untuk alokasi Mesin Virtual, menjadi 1Gb saja sudah cukup.
  ![7](https://github.com/darblietz/Introduction-to-DevOps/assets/98991080/6833a6d2-5e48-4315-822e-4075663594f3)
  
  #### 8. Setelah itu Klik "Processors", dan Ganti " Number of processors cores" menjadi 1. dan Checklist "Virtualize Intel VT-x/EPT or AMD-V/RVI.
  ![8](https://github.com/darblietz/Introduction-to-DevOps/assets/98991080/b499c8c6-ad59-4a09-a861-56ed0f302718)
  
  #### 9. Klik "Network Adapter", dalam "Network connection" pilih Opsi "Bridged: Connected directly to the physical network".
  ![9](https://github.com/darblietz/Introduction-to-DevOps/assets/98991080/dcbce2aa-0eb0-471c-833d-cc9939aa7488)
  
  #### 10. Setelah di Close, maka Klik "Finish".
  ![10](https://github.com/darblietz/Introduction-to-DevOps/assets/98991080/65d1043a-bf1f-4cc5-ac2e-e2e2c8f1040b)
  
  #### 11. Tunggu proses, dan pilih bahasa yang di inginkan misal English, Klik done dibawah.
  ![12](https://github.com/darblietz/Introduction-to-DevOps/assets/98991080/1c1ed5c7-7dc7-4e3d-b218-e1b3ee4ad308)
  
  #### 12. Pilih "ens33 eth" dan "Edit IPv4"
  ![14](https://github.com/darblietz/Introduction-to-DevOps/assets/98991080/e199ff2c-05e3-4226-8ed8-68fd0ec3955a)
  
  #### 13. dan pilih Manual.
  ![15](https://github.com/darblietz/Introduction-to-DevOps/assets/98991080/80ec4509-0e5d-4060-8977-5338caa1c454)
  
  #### 14. isikan ip yang sesuai dengan jaringan terhubung diperangkat anda kecuali angka urutan ke4 diubah menjadi "0/24". dan Address 3 angka berurutan sama dengan ip kalian tapi yang angka ke 4 harus diubah dengan angka yang lain misal 244, tidak boleh melebihi 256. Gateway samakan. dan Name servers menggunakan server Google. dan terakhir Search domains kosongkan.
  ![16](https://github.com/darblietz/Introduction-to-DevOps/assets/98991080/c1237a4a-cd20-456a-a4ec-ce1236f7a80a)
  
  #### 15. Nahh inilah contoh melihat Ip kita, dengan menggunakan Windows powershell dan ketik "ipconfig".
  ![17](https://github.com/darblietz/Introduction-to-DevOps/assets/98991080/d2105498-0a6a-40ad-bc25-ce61bf51acc9)
  
  #### 16. Setelah di Done, maka muncul Guided storage configuration, pilih Custom storage layout.
  ![18](https://github.com/darblietz/Introduction-to-DevOps/assets/98991080/b6157ef1-b42c-4df5-96f1-97f67ffe9668)
  
  #### 17. Pilih "free space" di Avalaible Devices dan Add GPT Partition.
  ![19](https://github.com/darblietz/Introduction-to-DevOps/assets/98991080/9426a7b1-2b74-46c4-993d-c97db00c51a5)
  
  #### 18. Ubah Size jadi 8G dan Create.
  ![20](https://github.com/darblietz/Introduction-to-DevOps/assets/98991080/6fdf3583-0f1a-4718-9fa3-de1cce311a34)
  
  #### 19. Pilih "free space" lagi dan "Add GPT Partition".
  ![21](https://github.com/darblietz/Introduction-to-DevOps/assets/98991080/301560a2-82ba-42cd-987d-6eaab6a6f54f)
  
  #### 20. Ubah Size jadi 1G dan Format menjadi "swap" and Create.
  ![22](https://github.com/darblietz/Introduction-to-DevOps/assets/98991080/9845763f-3bf9-4ce1-a58b-4fdf95365896)
  
  #### 21. Dan pilih "Continue"
  ![23](https://github.com/darblietz/Introduction-to-DevOps/assets/98991080/6ed1ed34-ddf1-42ff-988d-4a7b0385612c)
  
  #### 22. Di Profile Setup kalian diminta untuk mengisi Username yang diawal kita sudah buat.
  ![24](https://github.com/darblietz/Introduction-to-DevOps/assets/98991080/de2fd39b-f86f-42c2-8c7d-528a67d97e16)
  
  #### 23. Pilih install OpenSSH server dan done.
  ![25](https://github.com/darblietz/Introduction-to-DevOps/assets/98991080/ea7fc64c-cc07-4c77-a09c-86410abacf51)
  
  #### 24. Tinggal tunggu penginstallan.
  ![26](https://github.com/darblietz/Introduction-to-DevOps/assets/98991080/c1c28d56-1695-4663-8193-14f8e5f746e3)
  
  
  
  
  
  
  
  
  
  
  
  
 
 
 
 
 
 
  
  

Markdown is a lightweight markup language based on the formatting conventions
that people naturally use in email.
As [John Gruber] writes on the [Markdown site][df1]

> The overriding design goal for Markdown's
> formatting syntax is to make it as readable
> as possible. The idea is that a
> Markdown-formatted document should be
> publishable as-is, as plain text, without
> looking like it's been marked up with tags
> or formatting instructions.

This text you see here is *actually- written in Markdown! To get a feel
for Markdown's syntax, type some text into the left window and
watch the results in the right.

## Tech

Dillinger uses a number of open source projects to work properly:

- [AngularJS] - HTML enhanced for web apps!
- [Ace Editor] - awesome web-based text editor
- [markdown-it] - Markdown parser done right. Fast and easy to extend.
- [Twitter Bootstrap] - great UI boilerplate for modern web apps
- [node.js] - evented I/O for the backend
- [Express] - fast node.js network app framework [@tjholowaychuk]
- [Gulp] - the streaming build system
- [Breakdance](https://breakdance.github.io/breakdance/) - HTML
to Markdown converter
- [jQuery] - duh

And of course Dillinger itself is open source with a [public repository][dill]
 on GitHub.

## Installation

Dillinger requires [Node.js](https://nodejs.org/) v10+ to run.

Install the dependencies and devDependencies and start the server.

```sh
cd dillinger
npm i
node app
```

For production environments...

```sh
npm install --production
NODE_ENV=production node app
```

## Plugins

Dillinger is currently extended with the following plugins.
Instructions on how to use them in your own application are linked below.

| Plugin | README |
| ------ | ------ |
| Dropbox | [plugins/dropbox/README.md][PlDb] |
| GitHub | [plugins/github/README.md][PlGh] |
| Google Drive | [plugins/googledrive/README.md][PlGd] |
| OneDrive | [plugins/onedrive/README.md][PlOd] |
| Medium | [plugins/medium/README.md][PlMe] |
| Google Analytics | [plugins/googleanalytics/README.md][PlGa] |

## Development

Want to contribute? Great!

Dillinger uses Gulp + Webpack for fast developing.
Make a change in your file and instantaneously see your updates!

Open your favorite Terminal and run these commands.

First Tab:

```sh
node app
```

Second Tab:

```sh
gulp watch
```

(optional) Third:

```sh
karma test
```

#### Building for source

For production release:

```sh
gulp build --prod
```

Generating pre-built zip archives for distribution:

```sh
gulp build dist --prod
```

## Docker

Dillinger is very easy to install and deploy in a Docker container.

By default, the Docker will expose port 8080, so change this within the
Dockerfile if necessary. When ready, simply use the Dockerfile to
build the image.

```sh
cd dillinger
docker build -t <youruser>/dillinger:${package.json.version} .
```

This will create the dillinger image and pull in the necessary dependencies.
Be sure to swap out `${package.json.version}` with the actual
version of Dillinger.

Once done, run the Docker image and map the port to whatever you wish on
your host. In this example, we simply map port 8000 of the host to
port 8080 of the Docker (or whatever port was exposed in the Dockerfile):

```sh
docker run -d -p 8000:8080 --restart=always --cap-add=SYS_ADMIN --name=dillinger <youruser>/dillinger:${package.json.version}
```

> Note: `--capt-add=SYS-ADMIN` is required for PDF rendering.

Verify the deployment by navigating to your server address in
your preferred browser.

```sh
127.0.0.1:8000
```

## License

MIT

**Free Software, Hell Yeah!**

[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen. Thanks SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax)

   [dill]: <https://github.com/joemccann/dillinger>
   [git-repo-url]: <https://github.com/joemccann/dillinger.git>
   [john gruber]: <http://daringfireball.net>
   [df1]: <http://daringfireball.net/projects/markdown/>
   [markdown-it]: <https://github.com/markdown-it/markdown-it>
   [Ace Editor]: <http://ace.ajax.org>
   [node.js]: <http://nodejs.org>
   [Twitter Bootstrap]: <http://twitter.github.com/bootstrap/>
   [jQuery]: <http://jquery.com>
   [@tjholowaychuk]: <http://twitter.com/tjholowaychuk>
   [express]: <http://expressjs.com>
   [AngularJS]: <http://angularjs.org>
   [Gulp]: <http://gulpjs.com>

   [PlDb]: <https://github.com/joemccann/dillinger/tree/master/plugins/dropbox/README.md>
   [PlGh]: <https://github.com/joemccann/dillinger/tree/master/plugins/github/README.md>
   [PlGd]: <https://github.com/joemccann/dillinger/tree/master/plugins/googledrive/README.md>
   [PlOd]: <https://github.com/joemccann/dillinger/tree/master/plugins/onedrive/README.md>
   [PlMe]: <https://github.com/joemccann/dillinger/tree/master/plugins/medium/README.md>
   [PlGa]: <https://github.com/RahulHP/dillinger/blob/master/plugins/googleanalytics/README.md>
