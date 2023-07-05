# PA-PC_202131133_M-FAJRIN-WIRATTAMA_F

# WORD SEGMENTATION

Pemisahan kata, juga dikenal sebagai segmensi kata, adalah proses membagi teks berbahasa alami menjadi kumpulan kata yang berbeda.Segmentasi kata, yang sering digunakan dalam Python, digunakan dalam pemrosesan teks dan pemodelan bahasa dengan tujuan menemukan batas kata dalam teks yang tidak memiliki pemurnian kata yang jelas. Misalnya, jika Anda memiliki teks dalam bahasa Tionghoa atau bahasa lain yang tidak menggunakan spasi sebagai pemisah kata, Anda harus menggunakan teknik segmentasi kata untuk membagi teks menjadi satuan kata yang berbeda. Segmensi kata seringkali merupakan tahap awal pemrosesan bahasa alami, atau natural language processing, sebelum melakukan analisis atau tugas lainnya pada teks.

Untuk melakukan word segmentation dalam Jupyter Notebook, ikuti langkah-langkah berikut:

1. Mempersiapkan lingkungan: Pastikan Anda telah menginstal pustaka NLP yang dibutuhkan di lingkungan Jupyter Notebook dapat dengan menggunakan conda atau pip untuk menginstal pustaka seperti NLTK, SpaCy, atau pustaka bahasa seperti PyThaiNLP.

2. Impor pustaka: Sebelum dapat menggunakan Jupyter Notebook, harus mengimpor pustaka yang diperlukan. Jika menggunakan NLTK, Anda dapat menggunakan perintah "import nltk" untuk melakukannya.

3. Inisialisasi pustaka: Beberapa pustaka sintaksis bahasa perlu diinisialisasi sebelum dapat digunakan. Misalnya, untuk menggunakan SpaCy, harus menggunakan perintah "nlp = spacy.load('en')" untuk bahasa Inggris atau "nlp = spacy.load('zh')" untuk bahasa Tionghoa.

4. Baca dan persiapkan teks: untuk dapat membaca teks yang ingin disegmenkan ke dalam Jupyter Notebook. atau juga dapat menulis teks langsung ke dalam kode Python atau membacanya dari berkas teks atau sumber data lainnya.

5. Membagi kata: Gunakan fungsi atau metode yang disediakan oleh pustaka NLP yang digunakan untuk melakukan pembagian kata. Misalnya, jika menggunakan NLTK, dapat menggunakan fungsi "word_tokenize()" untuk memisahkan kata-kata dalam teks, dan jika menggunakan SpaCy, dapat menggunakan objek "nlp" yang telah diinisialisasi untuk memproses teks dan mendapatkan kata-kata khusus.

6. Tampilkan hasil: Setelah melakukan segmentation kata, untuk menampilkan kata-kata yang telah dipisahkan ke dalam Jupyter Notebook dapat dengan menggunakan fungsi "print()" atau metode lain yang sesuai dengan tujuan.

Aplikasi pemrosesan bahasa alami seperti penerjemahan mesin, analisis teks, klasifikasi teks, dan banyak lagi membutuhkan segmentasi kata yang baik untuk memproses dan memahami teks dengan lebih baik dan menghasilkan hasil analisis yang lebih relevan dan tepat.
