# Pertemuan ke-1, (14/04/2025)
----------
## Mini-Task CLI Usage (powershell)

``` powershell

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

## Note
### Dokumentasi
- Package Manager untuk install software https://scoop.sh/
- command powershell di https://learn.microsoft.com/en-us/
- Markdown Guide di https://www.markdownguide.org/ 
- untuk flowchart mermaid di https://mermaid.js.org/

### Basic Command
- mkdir (create)
- dir (read) 
- rmdir (delete folder)
- del (delete file)
- cls (clear terminal)
- cd (pindah directory)
- echo (cetak task)

### Loop di Powershell
```powershell

For ($i = 0; $i -lt 5; $i++){
echo "command nya disini, Ex/: echo $1"
}

```
### cara mengakses directory menggunakkan cd
1. ```cd ..\..\..```
2. ```cd folder1\folder2\folder3```
3. ```cd ~``` (untuk kembail ke home)
4. ``` cd ``` + Tab untuk auto

