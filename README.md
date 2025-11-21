

## 1. Install Git

Download & install Git untuk Windows:
[https://git-scm.com/download/win](https://git-scm.com/download/win)

Cek instalasi buka powershell/CMD:

```sh
git --version
```

---

## 2. Clone Repository

```sh
git clone https://github.com/Chihiroryuu/STupdater.git
cd STupdater
```

---

## 3. Install Python

Download Python untuk Windows:
[https://www.python.org/downloads/](https://www.python.org/downloads/)

Pastikan centang **"Add Python to PATH"** saat instalasi.

Cek instalasi:

```sh
python --version
```

---

## 4. Jalankan Script (installer.py)

```sh
python installer.py
```

Jika perlu environment variable:

```sh
set API_KEY=apikey_kamu
python installer.py
```

(PowerShell)

```powershell
$env:API_KEY = "apikey_kamu"
python installer.py
```

---

## 5. Dependencies

Tidak ada dependency tambahan. Cukup Python + file `installer.py`.

---

## 6. Troubleshooting

* **Python tidak dikenali** → Python belum masuk PATH.
* **Error saat jalan** → Pastikan file berada dalam folder yang benar.

---


JIKA TIDAK MAU RIBET DOWNLOAD INI AJA EXTRACT & INSTALL

https://drive.google.com/file/d/1RFd-hlsgyZkvhXMljHsXgCDT42GffG6O/view?usp=drive_link
