
# Submission Dicoding "Belajar Analisis Data dengan Python"

## Proyek Analisis Data "Dashboard E-Commerce Brazil :convenience_store:"
Repository ini berisi proyek data analisis yang saya kerjakan.

## Deskripsi
Proyek ini bertujuan untuk menganalisis data pada E-Commerce Public Dataset yang diambil dari [Brazilian E-Commerce Public Dataset by Olist (kaggle.com)](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce). Tujuan akhir dari proyek ini adalah untuk menghasilkan sebuah *insight* yang berguna dari data yang dianalisis.

## Struktur Direktori

-  **/submission**: Direktori induk proyek yang di dalamnya terdapat file README.md besertakan folder lainnya.
-  **/dashboard**: Direktori ini berisi file-file yang bersangkutan dengan *deployment* aplikasi Streamlit dari hasil analisis dataset.
-  **/data**: Direktori ini berisikan berbagai dataset yang berasal dari [Brazilian E-Commerce Public Dataset by Olist (kaggle.com)](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce), di mana pada bagian nama telah dihilangkan bagian "olist_".
- **notebook.ipynb dan notebook_local.ipynb**: Merupakan file notebook tempat analisis dataset dilakukan. **notebook.ipynb** diperuntukkan bila akan dijalankan di Google Colab, sedangkan **notebook_local.ipynb** untuk aplikasi Jupyter Notebook lokal (Anaconda, Miniconda, dll).

## Instalasi 

*Karena alasan batasan ukuran file, untuk bisa menjalankan aplikasi Streamlit secara lokal diharuskan menjalankan file notebook yang terlampirkan guna membuat dataset baru (all_data.csv dan customer_plotmap.csv). Dataset tersebut akan digunakan di aplikasi Streamlit.

1. Unduh repo ini sebagai ZIP.
	- Jika memakai Google Colab, ekstrak di mana saja, lalu upload folder **submission** beserta segala isinya ke halaman awal atau direktori paling luar dari Google Drive Anda. 
	- Jika memakai Jupyter Notebook lokal, ekstrak ke direktori kerja dari Anaconda/Miniconda (secara *default* terletak di direktori "C:\Users\username"

2. Masuk ke dalam direktori **submission**, pilih **notebook.ipynb** bila akan dijalankan di Google Colab, sedangkan **notebook_local.ipynb** jika dijalankan pada aplikasi Jupyter Notebook lokal.
	- Agar bisa dijalankan di perangkat lokal, terlebih dahulu membuat *environtmet* baru.
		```shell
		conda create --name <nama_env>
		conda activate <nama_env>
		cd submission
		pip install -r requirements.txt
		jupyter-notebook .
		```

## Setup Environment Streamlit App

*Untuk menjalankan aplikasi Streamlit, digunakan mesin lokal (conda).

1. Masuk ke direktori **dashboard**
	```shell
	cd submission\dashboard
	```
2. Jalankan **dashboard.py**
	```shell
	streamlit run dashboard.py
	```

Atau bisa dengan mengunjungi laman [Proyek Analisis Data]().
