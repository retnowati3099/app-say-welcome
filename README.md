## Go-Modules
Go-Modules mulai dikenalkan  di Go-lang 1.11 dan 1.12.
Dengan Go-Modules, project dapat dibuat dengan mudah dan management dependency juga sangat mudah.

## Membuat module
Menggunakan perintah ```go mod init nama-modul```. Isinya berupa nama module dan versi Go-lang yang digunakan.

## Rilis Module
Golang terintegrasi baik dengan git.
Untuk merilis module, maka perlu membuat tag di Git

## Menambah Dependency
```go get nama-modul```

## Upgrade Modul
Membuat tag baru di Git.

## Upgrade Dependency
Mengubah isi go.mod, lalu mengubah tagnya menjadi tag yang baru.
Untuk download versi terbaru, gunakan perintah ```go get```.

## Major Update
Sebaiknya sebisa mungkin dihindari.
Namun jika tidak bisa dihindari, strateginya adalah mengubah nama modul.

#### Sumber belajar: Youtube Programmer Zaman Now