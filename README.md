# Pertemuan ke-1, (14/04/2025)
----------
## Mini-Task CLI Usage

#### Without Loop
```powershell
mkdir "Latihan CLI Dasar"
cd "Latihan CLI Dasar"
"type nul">latihan1.txt
"type nul">latihan2.txt
"type nul">latihan3.txt
"type nul">latihan4.txt
"type nul">latihan5.txt
dir
del latihan4.txt
mkdir "latihan4.txt"
del latihan5.txt
mkdir "latihan5.txt"
dir
rmdir "latihan4.txt"

```

#### With Loop
``` cmd
mkdir "Latihan CLI Dasar"
cd "Latihan CLI Dasar"
for %i in (1 2 3 4 5) do echo. >latihan%i.txtdir
del latihan4.txt
mkdir "latihan4.txt"
del latihan5.txt
mkdir "latihan5.txt"
dir
rmdir "latihan4.txt"

```

## Mini-Task-2 (cmd)
#### memindahkan file lagu ke folder sesuai nama artis nya

1. membuat folder sesuai nama artisnya
```cmd
for %i in ("Blackpink", "Linkin Park", "Evanescence") do mkdir %i
```

2. memindahkan file .mp3 ke folder sesuai nama artisnya
```cmd
for %i in (Blackpink, "Linkin Park", Evanescence) do move %i*.mp3 .\%i
```


## Note
### Dokumentasi
- Package Manager untuk install software https://scoop.sh/
- command powershell di https://learn.microsoft.com/en-us/
- Markdown Guide di https://www.markdownguide.org/ 
- untuk flowchart mermaid di https://mermaid.js.org/

### Basic Command

| Perintah  | Fungsi                                        |
|-----------|-----------------------------------------------|
| `mkdir`   | Membuat folder/direktori baru                 |
| `cd`      | Masuk ke direktori/folder tertentu            |
| `cd ..`   | Naik satu level direktori                     |
| `cd ~`    | Kembali ke direktori home                     |
| `dir`     | Melihat isi direktori saat ini                |
| `del`     | Menghapus file                                |
| `rmdir`   | Menghapus folder kosong                       |
| `echo`    | Menampilkan teks/output ke terminal           |
| `cls`     | Membersihkan layar terminal                   |
| `type`    | Melihat isi dari file teks                    |
| `Tab`     | Auto-complete nama folder/file saat mengetik  |

### Loop di Powershell
```powershell

For ($i = 0; $i -lt 5; $i++){
echo "command nya disini, Ex/: echo $1"
}

```
### Navigasi folder menggunakkan `cd`

| Tujuan                          | Perintah                                |
|----------------------------------|------------------------------------------|
| Naik ke direktori atas          | `cd ..\..\..`                            |
| Masuk ke folder bertingkat      | `cd folder1\folder2\folder3`             |
| Kembali ke direktori Home user  | `cd ~`                                   |
| Auto-complete saat ketik folder | Ketik `cd` lalu tekan `[Tab]`            |

### Catatan Markdown

| Fitur         | Syntax                                      |
|---------------|----------------------------------------------|
| Tautan        | `[teks](https://example.com)`                |
| Gambar        | `![alt text](./gambar.jpg)`                  |
| Tabel (dasar) | Gunakan `|` dan `-` untuk membuat baris tabel|
| Code block    | Gunakan tiga backticks (```) di atas dan bawah kode |
| Bold/Italic   | `**bold**`, `*italic*`, `~~strikethrough~~`  |
