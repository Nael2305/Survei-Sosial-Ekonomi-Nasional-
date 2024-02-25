(Data yang disajikan berikut adalah data yang sudah diolah dari Survei Sosial Ekonomi Nasional September 2019, di mana data berikut adalah data yang sudah diagregasi ke tingkat kabupaten/kota. Tidak ada personally identifiable information yang muncul dalam data berikut.)

Anda diminta untuk melihat determinan tingkat pendapatan per kapita kabupaten/kota di seluruh Indonesia. Untuk itu, anda diminta untuk menguji beberapa hipotesis awal untuk menentukan variabel apa saja yang menjadi determinan tingkat pendapatan. Anda akan menggunakan data dari Survei Sosial Ekonomi Nasional, yaitu survei yang diadakan Badan Pusat Statistik sebanyak dua kali dalam setahun yang memberikan informasi mengenai potret kondisi sosioekonomi masyarakat. File yang akan diberikan bernama homework_4.csv

Untuk hipotesis pertama, anda diminta untuk menguji hipotesis bahwa tingkat pendapatan per kapita suatu daerah dipengaruhi secara positif oleh tingkat pendidikan yang lebih tinggi, tingkat urbanisasi yang lebih tinggi dan lokasi geografis di wilayah tertentu.

Dalam hipotesis kedua, anda diminta untuk menguji hipotesis bahwa tingkat pendapatan per kapita suatu daerah dipengaruhi secara positif oleh ukuran sektor formal. Asumsi yang berlaku adalah aktivitas ekonomi di sektor formal memiliki produktivitas yang lebih tinggi dibandingkan aktivitas ekonomi di sektor informal, sehingga berpengaruh positif terhadap tingkat pendapatan suatu daerah.

Tingkat pendapatan per kapita direpresentasikan oleh variabel exp_cap, yaitu pengeluaran per kapita dalam sebulan di suatu kota/kabupaten. Terdapat pula variabel log_exp_cap, yaitu pengeluaran per kapita dalam sebulan yang telah ditransformasi ke dalam bentuk natural log.

Tingkat pendidikan direpresentasikan oleh dua variabel: perc_smp, yaitu persentase penduduk di kota/kabupaten yang minimal telah menyelesaikan pendidikan setingkat SMP, dan perc_sma, yaitu persentase penduduk di kota/kabupaten yang minimal telah menyelesaikan pendidikan setingkat SMA.

Tingkat urbanisasi dipresentasikan oleh variabel perc_urban, yaitu persentase penduduk di kabupaten/kota yang tinggal di daerah perkotaan, sesuai definisi BPS.

Ukuran sektor formal direpresentasikan oleh variabel perc_formal, yaitu persentase tenaga kerja di kabupaten/kota yang bekerja di sektor formal, sesuai definisi BPS.

Lokasi geografis direpresentasikan oleh dua variabel: region1, yang mengindikasikan apakah kota/kabupaten terletak di Indonesia bagian Barat atau Indonesia bagian Timur. Terdapat juga variabel region2, yang mengindikasikan apakah kota/kabupaten terletak di salah satu dari wilayah berikut: "Sumatera", "Jawa", "Kalimantan", "Bali & Nusa Tenggara", "Sulawesi", dan "Maluku & Papua". Sumatera, Jawa, dan Kalimantan termasuk dalam Indonesia bagian Barat sedangkan Bali & Nusa Tenggara, Sulawesi, dan Maluku & Papua termasuk dalam Indonesia bagian Timur.

