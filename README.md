# Opds-indirici
OPDS Katalog İndirici — Kurulum ve Kullanım

Python ile yazılmış OPDS katalog indirici.
EPUB ve PDF kitaplarını OPDS kataloglarından indirir.

Özellikler

EPUB ve PDF desteği

Recursive kategori gezme

Paralel indirme

Yazar klasörleri oluşturma

Android / Termux desteği

Windows / Linux desteği

Progress bar



---

Gereksinimler

Python 3.10+

pip

requests modülü



---

Kurulum

1. Repoyu klonla


1. Requests modülünü kur

pip install requests

Termux kullanıyorsanız:

pkg install python
pip install requests


---

Çalıştırma

Windows / Linux

python opds_downloader.py

Bazı sistemlerde:

python3 opds_downloader.py


---

Android (Termux)

Depolama izni ver

termux-setup-storage

İzin penceresine onay verin.

Scripti çalıştır

python opds_downloader.py


---

Kullanım

Program sizden bir OPDS katalog URL’si ister.

Örnek:

https://example.com/opds

Daha sonra:

Kategorileri gezebilirsiniz

Kitap seçebilirsiniz

Tekli / çoklu / aralık seçimi yapabilirsiniz


Örnek seçimler:

5
1,3,7
1-20
h


---

İndirilen Dosyalar

Android / Termux

/storage/emulated/0/Download/KATALOG_ADI/

Windows

C:\Users\KULLANICI\Downloads\KATALOG_ADI\

Linux

~/Downloads/KATALOG_ADI/


---

Desteklenen Formatlar

EPUB

PDF



---

Hata Çözümü

requests modülü eksik

pip install requests


---

Permission denied

Termux’ta:

termux-setup-storage


---

python komutu bulunamadı

Linux:

sudo apt install python3

Termux:

pkg install python




BU KOD ANDROİDDE YAPAY ZEKAYLA YAZILMIŞ OLUB YANLIZCA ANDROİDDE DENENMİŞTİR.BİLGİSAYARDA ÇALIŞICAĞINI GARANTİ ETMEM

