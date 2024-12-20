1. Buka Folder di VS Code atau Terminal
Di VS Code:
Buka VS Code.
Klik File > Open Folder > Arahkan ke folder tempat file dashboard.py berada.
Pilih folder, lalu klik Open.
Di Terminal:
Buka terminal.
Gunakan perintah cd untuk berpindah ke folder tempat file dashboard.py berada, contoh:
- cd /path/to/your/project/folder

2. Periksa atau Instal Library yang Dibutuhkan
Pastikan Anda sudah memiliki pustaka yang tercantum di requirements.txt.
Jika belum, instal semua pustaka dengan menjalankan perintah berikut di terminal:
- pip install -r requirements.txt

3. Jalankan Dashboard dengan Streamlit
Ketik perintah berikut di terminal:
- streamlit run dashboard.py
Gantilah dashboard.py dengan nama file Python Anda jika berbeda.
Pastikan Anda menjalankan perintah ini di folder tempat file tersebut berada.
dan pastikan link ke path dataset sudah benar karena yang di github itu digunakan untuk deploy streamlitnya ya kak.

4. Akses Dashboard di Browser
Setelah menjalankan perintah di atas:
Streamlit akan otomatis membuka URL http://localhost:8501 di browser.
Jika browser tidak terbuka secara otomatis, Anda dapat membuka URL tersebut secara manual di browser.
