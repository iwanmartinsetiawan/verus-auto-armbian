# verus-auto-armbian
Script Autorun miner verush coin in Armbian

How to install
1. Buka terminal armbiannya.
2. Masukkan perintah dibawah 
```
wget -L https://raw.githubusercontent.com/iwanmartinsetiawan/verus-auto-armbian/main/miner.sh
```
4. edit file miner.sh yang telah didownload sebelumnya.
```
wallet = ganti dengan wallet address verus kalian
workername = nama worker yang akan digunakan. Contoh : node-01
```
6. ketik command dibawah di terminal, untuk edit crontab
```
crontab -e
```
3. Tambahkan script dibawah
```
@reboot bash /root/miner.sh
```
4. Save dan quit.
