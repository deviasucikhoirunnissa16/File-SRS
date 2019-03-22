<h1 align="center" id="software-requirements-specification">DOCUMENTASI PROYEK RPL
<p align="center"><font size="5"><b>SOFTWARE REQUIREMENTS SPECIFICATIONS</b></font><br>
"Aplikasi Ujian Online Di Sman 1 Jatibarang Berbasis Website (Uline)"</p></h1>

<p align="center"><img src="Gambar/POLINDRA.png" width="250" height="250"></p>

<br>

<p align="center">
    <b><font size="4">Kelompok 4:</font></b><br>
    1. Devia Suci Khoirun Nissa (1703076) <br>
    2. Kastuti (1703062)<br>
    3. Reza Pahlevi Yahya (1703069)
</p>
<center><font size="3"><p align="center">Kelas D3TI2C</p></font></center>

<br>

<br>

<p align="center"><b><font size="5">D3 TEKNIK INFORMATIKA</font></b><br>
<b><font size="3">POLITEKNIK NEGERI INDRAMAYU</font></b><br>
<b><font size="3">2019</font></b></p>


<b>
<h1>
<i>SOFTWARE REQUIREMENTS SPECIFICATIONS (SRS)</i>
</h1>
</b>

<ol>
	<li>Pendahuluan</li>
	<ol>
		1.1 Tujuan<br>
		1.2 Lingkup<br> 
		1.3 Definisi, Akronim dan Singkatan<br>
		1.4 Referensi<br>
		1.5 Overview<br>
	</ol>
	<li> Gambaran Umum</li>
	<ol>
		2.1 Perspektif Produk<br>
		<ol>
			2.1.1 Antarmuka Sistem<br>
			<ol>
				2.1.1.1 Use Cases Siswa<br>
				2.1.1.2 Use Cases Guru<br>
				2.1.1.3 Use Cases Siswa<br>
			</ol>
			2.1.2 Antarmuka Pengguna<br>
			2.1.3 Antarmuka Perangkat Keras<br>
			2.1.4 Antarmuka Perangkat Lunak<br>
			2.1.5 Antarmuka Komunikasi<br>
			2.1.6 Batasan-Batasan Memori<br>
			2.1.7 Operasi-Operasi<br>
			2.1.8 Kebutuhan-Kebutuhan dalam Tahapan Adaptasi<br>
		</ol>
		2.2 Fungsi-Fungsi Produk<br>
		2.3 Karakteristik Pengguna<br>
		2.4 Batasan-Batasan<br>
		2.5	Asumsi-Asumsi dan Ketergantungan/Keterkaitan<br>
		2.6	Kebutuhan-Kebutuhan Penyeimbang<br>
	</ol>
	<li> Kebutuhan Lain yang Spesifik</li>
	<ol>
		3.1	Performa<br>
		3.2	Keamanan Aplikasi<br>
	</ol>
	<li> Informasi Pendukung</li>
</ol>
		

<b>
1. Pendahuluan<br>
</b>
<ol>
	1.1 Tujuan<br>
	<ol>Dokumen ini akan menyajikan deskripsi rinci tentang aplikasi ULine yang akan dikembangkan. Dokumen ini akan menjelaskan mengenai spesifikasi pada aplikasi ULine seperti fitur sistem, antarmuka sistem, sistem apa yang akan dilakukan, apa saja kendala pada saat aplikasi beroperasi dan bagaimana sistem akan bereaksi pada saat sedang digunakan oleh user.<br></ol>
	1.2 Lingkup<br>
	<ol>Dokumen ini menyediakan acuan untuk pengendalian tentang aplikasi ULine. Adapun ruang lingkup pembuatan aplikasi ini adalah berbasis website yang memilih fasilitas yang ada yaitu :<br>
		<ol>
			<li> Admin sebagai pengelola atau CRUD (Creat, Read, Update, Delete) data guru, siswa dan mata pelajaran yang ada pada fitur-fitur aplikasi ULine seperti tambah data guru, siswa dan mata pelajaran serta mendaftarkan akun guru dan siswa.</li>
			<li>Guru sebagai pengelola atau CRUD (Creat, Read, Update, Delete) data mata pelajaran yang diampu, soal ujian dan jadwal ujian yang ada pada fitur-fitur aplikasi ULine seperti tambah data soal, pertanyaan, jawaban dan jawaban benarnya serta tambah jadwal ujian.</li>
		</ol>
	</ol>
	1.3 Definisi, Akronim dan Singkatan<br>
	<ol>Adapun definisi dari dokumen tersebut adalah :<br>
		<table>
			<tr>
			   	<td>No</td>
			   	<td>Akronim</td>
			   	<td>Singkatan</td>
			</tr>
			<tr>
				<td>1</td>
			   	<td>SPMP</td>
			   	<td>Software Project Management Plan</td>
			</tr>
			<tr>
				<td>2</td>
				<td>SRS</td>
			   	<td>Software Requirements Specifications</td>
			</tr>
			<tr>
			   	<td>3</td>
			   	<td>SDD</td>
			   	<td>Software Design Document</td>
			</tr>
			<tr>
			   	<td>4</td>
			   	<td>CRUD</td>
			   	<td>Creat, Read, Update dan Delete</td>
			</tr>
			<tr>
			   	<td>5</td>
			   	<td>IEEE</td>
			   	<td>International Institute of Electronic and Electrical Engineers</td>
			</tr>
			<tr>
			   	<td>6</td>
			   	<td>ULine</td>
			   	<td>Ujian Online</td>
			</tr>
		</table>
	</ol>
	1.4 Referensi<br>
		<ol>
		<ol>
			<li>IEEE. IEEE Std 830-1998 IEEE Recommended Practice for Software Requirements Specifications.</li>
		</ol>
		</ol>
	1.5 Overview<br>
	<ol>Penulisan dokumen SRS ini dibagi menjadi beberapa bab sebagai berikut:<br>
		BAB I berisi pendahuluan, menjelaskan mengenai Tujuan pembuatan dokumen SRS, Lingkup, Definisi (Akronim atau Singkatan), Referensi dan Overview.<br>
		BAB II menjelaskan keseluruhan deskripsi dari Aplikasi ULine (Ujian Online). Deskripsi umum tersebut memberikan gambaran lengkap mengenai semua fungsi yang akan dilakukan oleh sistem.<br>
		BAB III berisi penjelasan detail dari masing-masing kebutuhan lain yang spesisik.<br>
		BAB IV berisikan tentang uraian mengenai informasi pendukung dalam pembuatan proyek Aplikasi ULine.<br>
	</ol>
</ol>