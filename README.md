# Dasar-Dasar Markdown
Tutorial markdown bahasa Indoensia. Versi resmi how-to markdown (berbahasa inggris) dapat dibaca [disini](http://daringfireball.net/projects/markdown/ "Daringfireball Markdown") atau [disini](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet "Cheatsheet").

## Environment
Penulis menggunakan sistem operasi windows 8.1. Sistem operasi lain bisa menyesuaikan dengan penjelasan dibawah.

## Bagian Membosankan: Teori
### Apa itu markdown?
Markdown adalah satu bahasa yang diciptakan untuk mempermudah pembuatan dan pembacaan kode HTML. Markdown diciptakan dalam bahasa Perl. Format tulisan markdown sendiri adalah plain-text yang artinya kamu bisa membuat markdown dari text-editor biasa seperti notepad, sublime, emacs, vi, vi, dll. Lisensi markdown sendiri adalah opensource BSD.

### Bagaimana cara membuat dokumen markdown?
Caranya mudah. Cukup install perl dan pasang library markdown.
 1. Pertama-tama komputer atau laptop kamu harus sudah terinstall perl, jika belum kamu bisa download dari [sini](http://strawberryperl.com/).
 2. Jika sudah terinstall perl, kamu bisa mendownload library markdown dari [sini](http://daringfireball.net/projects/downloads/Markdown_1.0.1.zip).
 3. Buat file markdown. Jika kamu belum bisa membuat, kamu bisa menggunakan contoh file markdown [disini](Simple.md)
 4. Compile file markdown dengan perintah `perl Markdown.pl --html4tags file_kamu.md`. Perintah tersebut akan menghasilkan output file html yang dapat kamu buka lewat browser.

### Ada nggak cara lain yang lebih mudah?
Ada. Rekomendasi saya adalah dengan menggunakan Sublime Text 3. Dengan menggunakan ST3, kamu dapat menggunakan markdown dengan mudah.
 1. Buka Sublime Text 3. Jika belum download silahkan download dan install ST3 terlebih dahulu [disini](http://www.sublimetext.com/3).
 2. Buka package manager dengan menggunakan perintah `ctrl+shift+p`. Jika kamu belum memiliki package manager, install terlebih dahulu [disini](https://packagecontrol.io/installation).
 3. Pilih menu Install Package.
 4. Pilih plugin MarkdownEditing.
 5. Buka lagi package manager.
 6. Pilih Markdown Preview.
 7. Buat file markdown. Jika kamu belum bisa membuat, kamu bisa menggunakan contoh file markdown [disini]().
 8. Untuk melihat hasil markdown dalam bentuk file html, kamu membuka konsol perintah dengan `ctrl+shift+p` kemudian kamu dapat memilih perintah Markdown Preview: Preview In Browser.
 9. Browser akan terbuka untuk memperlihatkan hasil konversi markdown ke html.

### Oke, aku siap untuk membuat markdown. Lalu apa?
Kamu dapat mempelajari syntax markdown. Bagian dibawah akan menjelaskan lebih lanjut tentang syntax markdown.

## Funny Time
### Paragraf
Membuat paragraf pada markdown sangat mudah. Cukup mengetikkan sesuatu maka apa yang kamu ketikkan akan otomatis dikonversi menjadi paragraf selama kamu belum mengetikkan `enter`. Jadi `enter` adalah tanda awal paragraf.
### Heading
Heading, biasa juga disebut sebagai judul. Membuat judul cukup dilakukan dengan kode hash `#`. Contohnya untuk membuat `<h1>Ini Judul Paragraf</h1>` di markdown syntaxnya adalah `# Ini Judul Paragraf`. Kamu dapat menggunakan `#` dari satu sampai 6 yang menandakan level tag `h` yang akan kamu buat. Contohnya `<h3>Ini Heading Level 3</h3>` dapat dibuat dengan syntax markdown `### Ini Heading Level 3`.
### Bold
Efek bold dapat dibuat dengan menggunakan syntax `**`. Misal untuk membuat `<b>Bold</b>` digunakan syntax `**Bold**` pada markdown.
**Bold**
### Efek Italyc
Efek italyc dapat dibuat dengan menggunakan syntax `*`. Misal untuk membuat `<i>Italyc</i>` digunakan syntax `*Italyc*` pada markdown.
*Bold*
### Blockquote
Blockquote dapat dibuat dengan syntax `>this is block quote` yang akan menghasilkan `<blockquote>this is block quote</blockquote>`.
>this is block quote
### Ordered List
Ordered list atau daftar terurut adalah penomeran dari daftar item. Pembuatan `<ol><li>1. List satu</li><li>2. List dua</li></ol>` dapat dilakukan dengan sederhana mengetikkan `spasi` + `nomer` pada paragraf baru (harus mengetikkan enter terlebih dahulu). Contoh ` 1 List 1` akan menghasilkan
 1 List Satu
### Unordered List
Unorderet list atau daftar tak terurut dibuat dengan cara yang hampir sama dengan ordered list, namun jika ordered list menggunakan angka unordered list menggunakan `*`
 * Satu
 * Dua
 * Tiga
### Hyperlink
Hyperlink pada markdown cukup singkat. Untuk membuat `<a href='http://yourlink.com'>Your Link</a>` cukup ketikkan syntax `[Your Link](http://yourlink.com)`.
### Horizontal Rule
Horizontal rule pada markdown dapat dibuat dengan syntax `---` lalu ketik `enter`. Syntax ini akan menghasilkan:

---
