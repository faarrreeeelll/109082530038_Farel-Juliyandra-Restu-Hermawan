# <h1 align="center">Laporan Praktikum Modul 2 - ... </h1>
<p align="center">[Farel Juliyandra Restu Hermawan] - [109082530038]</p>

## Unguided 

### 1. [Soal Latihan Modul 2A]
#### soal1.go

```go
package main

import "fmt"

func main() {
	var (
		satu, dua, tiga string
		temp            string
	)
	fmt.Print("Masukan input string: ")
	fmt.Scanln(&satu)
	fmt.Print("Masukan input string: ")
	fmt.Scanln(&dua)
	fmt.Print("Masukan input string: ")
	fmt.Scanln(&tiga)
	fmt.Println("Output awal = " + satu + " " + dua + " " + tiga)
	temp = satu
	satu = dua
	dua = tiga
	tiga = temp
	fmt.Println("Output akhir = " + satu + " " + dua + " " + tiga)
}
```
### Output Unguided :

##### Output 
![Screenshot Output Unguided 1_1]()
[program Go tersebut digunakan untuk menerima tiga input string dari pengguna, lalu menukar urutan nilainya. Program menampilkan urutan awal dari input, kemudian menggunakan variabel temp sebagai penyimpanan sementara untuk menukar posisi data, dan akhirnya menampilkan urutan baru setelah ditukar.]
