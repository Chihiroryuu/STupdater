1. Install Git
Download & install Git untuk Windows: https://git-scm.com/download/win
Cek instalasi:
git --version

2. Clone Repository
git clone https://github.com/Chihiroryuu/STupdater.git
cd STupdater
Ganti USERNAME/REPO sesuai repo kamu.

3. Install Python
Download Python untuk Windows: https://www.python.org/downloads/
Saat install, centang “Add Python to PATH”.
Cek instalasi:
python --version

4. Buat Virtual Environment (Opsional tapi Disarankan)
python -m venv .venv
.\.venv\Scripts\activate

5. (Tidak Ada Dependencies)
Project ini hanya memakai installer.py, jadi tidak perlu install library tambahan.

6. Jalankan installer.py
python installer.py
