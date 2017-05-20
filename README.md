# LuciverZone
## How to use github

### Yang perlu dilakukan sekali saja untuk inisial github
	$git config --global user.email "email github"
	$git config --global user.name "nama akun github"

### Remote github
	$git remote add origin ...

### Clone repo yang akan di manage
	$git clone <url dari repo>

### Masuk kedalam folder yang telah diclone
	$cd NamaFolder

### Tambahkan file kedalam folder

### Tambahkan file kedalam git untuk di commit
	$git add -A

### Commit (untuk menginisialisasi file yang akan di push)
	$git commit -m "...ini adalah pesan yang akan di sampaikan..."

### Push kedalam repo
	$git push origin master
	:: origin adalah letak url nya
	:: dan master adalah nama branch nya

## Jika Bekerja Secara Tim
### Untuk mengetahui perubahan repo
	$git clone

## Istilah-Istilah github
	### upstream
	### fork
	### branches
	### pull request
	### clone

	" branch paling banyak berguna jika kita melakukan kolaborasi"

## Label pada saat membuat issues

	- bug > masalah
	- enhancement > perlu diperbaiki
	- help wanted > butuh bantuan jika team tidak sanggup memperbaikinya
	- wontfix > tidak perlu diperbaiki
