Pengenalan
==========
Panduan ringkas ini adalah untuk mereka yang berminat untuk mempelajari
kaedah pembangunan laman web atau aplikasi web menggunakan *framework*
Django_. Django_ adalah *web framework* yang dibangunkan menggunakan bahasa
pengaturcaraan Python_.

======================
Kenapa Python/Django ?
======================
Anda mungkin tertanya-tanya kenapa perlu belajar Python berbanding bahasa
pengaturcaraan yang lain ? Python adalah antara bahasa pengaturcaraan umum
(*general purpose programming language*) yang kian meningkat adopsinya dalam
bidang pembangunan perisian. Anda boleh melihat penggunaannya bermula daripada
peranti-peranti kecil seperti telefon bimbit sehingga dalam bidang penyelidikan
di `NASA dan lain-lain organisasi penyelidikan`__.

Salah satu kelainan utama Python adalah pada sintaksnya yang sedikit berbeza
berbanding bahasa pengaturcaraan yang anda biasa jumpa. Python menggunakan
*whitespace* sebagai cara untuk membezakan setiap *block* kod berbanding
penggunaan token khas seperti 'begin, end', '{, }' dalam bahasa pengaturcara
lain. Contohnya::

    # Python
    if is_logged_in:
        print 'Selamat datang'

    // PHP
    if ($is_logged_in) {
        print 'Selamat datang';
    }

    // PHP
    if ($is_logged_in) {
    print 'Selamat datang';
    }

    // PHP
    if ($is_logged_in) {print 'Selamat datang';}

    // Ruby
    if is_logged_in
        print 'Selamat datang'
    end

Ini bermakna indentasi yang betul adalah sesuatu yang wajib dalam Python. Anda
mungkin merasakan ia suatu yang melecehkan namun apabila anda perlu membaca
kembali kod yang ditulis sama ada oleh anda sendiri atau orang lain, anda akan
dapati kod Python lebih senang untuk dibaca dan difahami. Ini sangat penting
kerana sedar atau tidak 80% masa dalam pengaturcaraan adalah dalam membaca kod
yang telah ditulis berbanding menulisnya. Malah dalam kebanyakkan projek yang
menggunakan bahasa selain Python, anda tetap diminta untuk meng'indent' kod
supaya lebih senang dibaca dan difahami.

Selain itu Python juga mempunyai koleksi *builtin standard libraries* yang secara
relatifnya amat komprehensif. *Library* untuk memanipulasi database sqlite, JSON,
XML, mencapai *network resources*, GUI toolkit, kriptografi, *data compression*, *multithreading/multiprocess* dan banyak lagi telah disertakan dalam Python. 

__ http://wiki.python.org/moin/OrganizationsUsingPython#Science

------
Django
------
Django adalah *framework* khusus untuk membangunkan aplikasi web menggunakan
Python. Antara lain, ia didatangkan dengan *tools* seperti:-

* ORM
* Automatic admin interface
* Template system
* User Authentication
* Session Management
* Form validation
* Internationalization - untuk pembangunan website dalam pelbagai bahasa.
* Cache system
* GIS/Spatial data
* Pagination
* Email sending framework
* Security, Cryptographic signing
* Comments system

=========
Keperluan
=========
Untuk panduan ini, saya menganggap pembaca akan menggunakan sistem operasi (OS)
Windows XP atau yang terkini. Aplikasi yang akan digunakan adalah seperti berikut:-

* PortablePython_
* `Notepad++`_
* Pelayar Web (Firefox/Google Chrome/Internet Explorer dll)

.. _Django: http://www.djangoproject.org/
.. _Python: http://www.python.org/
.. _PortablePython: http://www.portablepython.com/
.. _Notepad++: http://notepad-plus-plus.org/
