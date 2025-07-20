# Capstone Fadillah Rasyidin Frediant 
Analysis-of-Our-Gym-s-Fitness-Data
This repository is about Analysis of Our Gym's Fitness Data and I analyzed it using llm ibm-granite/granite-3.3-8b-instruct and I have analyzed the data that I have obtained from Kaggle which contains information about "male and female gym members"
Raw Dataset:https://www.kaggle.com/datasets/valakhorasani/gym-members-exercise-dataset/data
INSIGHT & FINDINGS:
Kesimpulan untuk Anggota Gym Pria 👨‍🦱
1. Demografi Usia:

Mayoritas Lansia/Senior: Kelompok usia Lansia/Senior memiliki proporsi terbesar (34.4%) di gym, diikuti oleh dewasa paruh baya dan dewasa muda. Remaja adalah kelompok paling sedikit.

2. Distribusi Berat Badan:

Middleweight Dominan: Mayoritas pria di gym berada dalam kategori berat badan Middleweight, diikuti oleh Lightweight dan Heavyweight. Featherweight adalah kategori dengan jumlah paling sedikit.

3. Hubungan Tinggi Badan vs. Usia:

Tidak Ada Korelasi Jelas: Tidak ada hubungan atau pola yang jelas antara tinggi badan dan usia pada anggota gym pria. Tinggi badan tersebar merata di berbagai kelompok usia.

4. Rata-rata Detak Jantung (BPM):

Pola Umum Fisiologis: Max BPM (sekitar 180) adalah yang tertinggi, diikuti oleh Avg BPM (sekitar 145), dan Resting BPM (sekitar 60-65) adalah yang terendah. Ini menunjukkan respons fisiologis yang normal terhadap aktivitas fisik.

5. Jenis Latihan:

Popularitas Merata: Latihan Strength, Yoga, dan Cardio memiliki popularitas yang relatif seimbang (sekitar 25-26% masing-masing). HIIT sedikit kurang populer dibandingkan ketiganya.

6. Tingkat Pengalaman:

Menengah Paling Banyak: Tingkat pengalaman Menengah adalah yang paling dominan (41.7%), diikuti erat oleh Pemula (38.6%). Anggota tingkat Lanjutan adalah yang paling sedikit.

Ringkasan Pria: Gym ini menarik populasi pria yang lebih tua, dengan sebagian besar berstatus menengah dan pemula dalam pengalaman, serta memiliki berat badan rata-rata hingga berat. Mereka cenderung berlatih kekuatan, yoga, dan kardio, dan menunjukkan respons detak jantung yang normal terhadap aktivitas.

Kesimpulan untuk Anggota Gym Wanita 👩‍🦱
Berikut adalah kesimpulan insight dan temuan dari semua grafik yang telah kita diskusikan mengenai anggota gym perempuan:

Secara keseluruhan, data menunjukkan keragaman yang signifikan di antara anggota gym perempuan dalam beberapa aspek, sementara di aspek lain ditemukan ketiadaan korelasi langsung dengan usia.

Temuan Utama:

Distribusi Berat Badan: Kategori Heavyweight mendominasi jumlah anggota perempuan, diikuti oleh Lightweight dan Middleweight yang relatif seimbang, dan Featherweight menjadi yang paling sedikit. Ini menunjukkan mayoritas anggota perempuan cenderung berada di kategori berat yang lebih tinggi.

Distribusi Usia: Kelompok Elderly/Senior merupakan segmen terbesar di antara anggota gym perempuan, sementara kategori Middle-aged, Teenager, dan Young Adult memiliki persentase yang cukup berimbang satu sama lain. Hal ini mengindikasikan gym ini berhasil menarik minat perempuan dari berbagai generasi, terutama yang lebih tua.

Hubungan Tinggi dan Usia: Tidak ada korelasi yang jelas antara tinggi badan dan usia anggota perempuan. Tinggi badan tidak menunjukkan tren naik atau turun seiring dengan bertambahnya usia, menyiratkan bahwa kedua faktor ini independen.

Jenis Latihan Favorit: Cardio dan Strength training adalah jenis latihan paling populer di kalangan perempuan, diikuti ketat oleh HIIT dan Yoga. Preferensi latihan terdistribusi relatif merata di antara keempat kategori utama ini.

Durasi Sesi dan Usia: Durasi sesi latihan tidak menunjukkan korelasi yang jelas dengan usia. Anggota dari berbagai kelompok usia memiliki durasi sesi yang bervariasi tanpa pola peningkatan atau penurunan yang konsisten.

Kalori Dibakar dan Usia: Mirip dengan durasi sesi, jumlah kalori yang dibakar tidak berkorelasi langsung dengan usia. Fluktuasi signifikan terlihat di semua rentang usia, menunjukkan bahwa faktor lain seperti intensitas atau jenis latihan lebih berpengaruh.

Persentase Lemak dan Usia: Tidak ada tren yang konsisten dalam persentase lemak rata-rata seiring bertambahnya usia. Meskipun ada fluktuasi, persentase lemak cenderung berada dalam rentang yang stabil (sekitar 25-30%), menunjukkan bahwa faktor individu lebih dominan daripada usia.

Ringkasan Wanita: Data menyoroti keanekaragaman demografis anggota gym perempuan (terutama dominasi Heavyweight dan Elderly/Senior) dan ketiadaan hubungan yang kuat antara usia dengan metrik kebugaran seperti tinggi badan, durasi sesi, pembakaran kalori, atau persentase lemak. Preferensi latihan cenderung terdistribusi secara seimbang.

AI SUPPORT EXPLANATION:
Dalam konteks notebook ini, "AI Support Explanation" merujuk pada output dari model AI (dalam hal ini, kemungkinan besar model bahasa atau asisten AI) yang digunakan untuk menjelaskan atau menganalisis suatu chart atau visualisasi data tertentu.
Dari cuplikan notebook yang Anda berikan, terlihat ada interaksi di mana pengguna meminta AI untuk:
Membuat chart: Contohnya, "create a bar chart to see the Fat_percentage of female members in a gym based on the age of the member".
Menjelaskan chart: Setelah chart "dibuat" (atau setidaknya instruksi pembuatannya diberikan), AI kemudian memberikan interpretasi atau wawasan (insights) dari chart tersebut.
Fungsi "AI Support Explanation" di Notebook ini:
Interpretasi Data Otomatis: AI membantu pengguna untuk mendapatkan wawasan langsung dari visualisasi data tanpa perlu menganalisis secara manual. Ini mempercepat proses pemahaman data.
Aksesibilitas: Membuat analisis data lebih mudah diakses oleh pengguna yang mungkin tidak memiliki keahlian mendalam dalam interpretasi grafik statistik.
Efisiensi: Mengurangi waktu dan upaya yang diperlukan untuk menarik kesimpulan dari data, karena AI dapat dengan cepat mengidentifikasi tren atau pola penting.
Penyediaan Konteks: AI dapat menambahkan konteks atau penjelasan tambahan yang relevan dengan data, seperti definisi istilah (misalnya Max_BPM, Avg_BPM, Resting_BPM) yang membantu pemahaman.
Generasi Kode (Implisit): Meskipun AI dalam konteks ini tidak menjalankan kode secara visual, ia menjelaskan bahwa kode Python (menggunakan pustaka seperti pandas, matplotlib, seaborn) akan diperlukan untuk menghasilkan chart yang diminta. Ini memberikan gambaran alur kerja untuk visualisasi data.
Contoh Spesifik dari Cuplikan Notebook:
Terlihat bahwa untuk permintaan tentang "Fat_percentage of female members in a gym based on the age of the member", AI memberikan output yang menjelaskan bahwa:
"A bar chart has been created to visualize the average fat percentage of female members in the gym based on their age."
"The chart titled "Average Fat Percentage of Female Members by Age" shows the x-axis representing age and the y-axis representing the average fat percentage."
AI juga secara transparan menyatakan keterbatasannya sebagai model teks: "Since I am an AI text-based model, I cannot directly execute code or display visual outputs like charts. The provided Python code snippet would generate the required bar chart if run in a suitable Python environment with the necessary libraries (pandas, matplotlib, and seaborn) installed and the dataframe df properly defined."
Jadi, "AI Support Explanation" dalam notebook ini adalah kemampuan AI untuk memahami permintaan terkait data/visualisasi, memberikan deskripsi tentang visualisasi yang relevan, dan menawarkan interpretasi awal dari data tersebut, sambil menjelaskan bagaimana visualisasi tersebut dapat dihasilkan secara programatik.
