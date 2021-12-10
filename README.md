<h1 align="center">
  AMBF
</h1>
<div align="center">
  <a href="https://github.com/anggaxd">
    <img alt="Python 3.9^" src="https://img.shields.io/badge/Python-3.9^-success.svg"/>
  </a>
  <a href="https://github.com/anggaxd">
    <img alt="Last Commit" src="https://img.shields.io/github/last-commit/anggaxd/ambf.svg"/>
  </a>
   <a href="https://github.com/anggaxd">
    <img alt="Repo Size" src="https://img.shields.io/github/repo-size/anggaxd/ambf.svg"/>
  </a>
  <a href="https://github.com/anggaxd">
    <img alt="Starts" src="https://img.shields.io/github/stars/anggaxd/ambf.svg"/>
  </a>
  <a href="https://github.com/anggaxd">
    <img alt="Forks" src="https://img.shields.io/github/forks/anggaxd/ambf.svg"/>
  </a>
</div>
<br>

jika kamu belum install termux kamu dapat mendownloadnya pada link dibawah

link download termux : https://f-droid.org/repo/com.termux_117.apk

untuk upgrade ke premium anda perlu membayar 20k ke : ``PULSA, OVO dan DANA``
lalu sertakan bukti transfer ke admin dan admin akan mengkonfirmasi api key anda

#### CARA UPGRADE KE PREMIUM
 - untuk harga sudah tertera di dalam script pada menu pendaftaran
 - kirim api key anda ke whatsapp [Admin](https://wa.me/6285864653276)
 - dan kirim bukti transfer ke whatsapp [Admin](https://wa.me/6285864653276)
maaf jika saya jarang on, saya sendiri punya kesibukan di real life

#### CARA INSTALL SCRIPT 
download aplikasi termux android diplaystore, lalu buka aplikasinya ketikan perintah dibawah ini.
```python
 pkg update && pkg upgrade
 pkg install python git -y
 pip install requests bs4 futures cython
 git clone https://github.com/anggaxd/ambf
```

#### MASUK KEDALAM FOLDER AMBF
```python
 cd $HOME/ambf
```

#### SETUP SCRIPT
```python
 python setup.py build_ext --inplace
 python run.py
```

#### JIKA INGIN UPDATE SCRIPT
ketik perintah di bawah ini untuk update tools
```python
 cd $HOME/ambf
 git pull
 rm -f *.so
 python setup.py build_ext --inplace
 python run.py
````

#### DISCLAIMER 
admin tidak bertanggung jawab dalam hal apapun !! 

#### CATATAN
gunakanlah dengan bijak, atas apapun yang terjadi admin tidak bertanggung jawab.
