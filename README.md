# encryption SHC

<li>Install SHC</li>
<pre><code>sudo apt-get update</code></pre>
<pre><code>sudo apt install build-essential</code></pre>
<pre><code>sudo apt-get install -y jq</code></pre>
<pre><code>sudo apt-get install shc</code></pre>

<li>Cara Pasang</li>
<pre><code>wget -q -O encshc "https://raw.githubusercontent.com/extracepat/enc/main/encshc" && chmod +x encshc</code></pre>
<li>Jalankan Perintah</li>
<pre><code>./encshc</code></pre>

Encryption menggunakan SHC tanpa ribet harus encrypt satu persatu ini tools untuk encrypt sekaligus berapapun yang mau di encrypt

<li>Penting!</li>
Buat folder enc di root secara manual lalu jalankan script tekan 1 done.
ini akan menencrypt seluruh file di dalam enc beserta sub folder nya
Contoh :

    ├── script.sh
    ├── folder1
    │   ├── subfolder1
    │   │   └── script1.sh
    │   └── subfolder2
    │       └── script2.sh
    └── folder2
        ├── subfolder3
        │   └── script3.sh
        └── subfolder4
            └── script4.sh
