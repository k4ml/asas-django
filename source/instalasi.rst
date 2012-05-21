Instalasi
=========
Kita mulakan dengan instalasi PortablePython. PortablePython adalah satu pakej Python beserta dengan *libraries* seperti Django, PIL (Python Imaging Libraries) dll yang mudah untuk di'install' pada komputer anda. URL untuk memuatturun aplikasi ini
adalah:-

http://portablepython.com/wiki/PortablePython2.7.3.1

Sila pilih *mirror* di bahagian bawah laman tersebut untuk memulakan proses muat-turun. Apabila selesai muat-turun, klik dua kali pada fail tersebut untuk melancarkan *installer*. Anda akan mendapat skrin seperti berikut:-

.. image:: ../images/installpy-1-p.png
    :align: center

Klik butang *next* dan anda seharusnya mendapat skrin berikut:-

.. image:: ../images/installpy-2-p.png
    :align: center

Klik butang *browse* untuk memilih lokasi *folder* untuk pemasangan. Saya cadangkan
anda *install* aplikasi ini di folder `C:\\Python`. Berikut cekupan skrin untuk step
ini:-

.. image:: ../images/installpy-3-p.png
    :align: center

.. image:: ../images/installpy-4-p.png
    :align: center

.. image:: ../images/installpy-5-p.png
    :align: center

Setelah menetapkan lokasi *folder*, langkah berikutnya adalah untuk memilih *libraries* untuk dimasukkan sekali dalam pemasangan ini. Sila pastikan Django dipilih:-

.. image:: ../images/installpy-6-p.png
    :align: center

Langkah terakhir adalah dengan menekan butang *Install* bagi memulakan proses instalasi. Anda akan melihat skrin berikut dipaparkan:-

.. image:: ../images/installpy-7-p.png
    :align: center

Proses instalasi akhirnya tamat.

.. image:: ../images/installpy-8-p.png
    :align: center

==============
Cuba Instalasi
==============
Sekarang mari kita pastikan proses instalasi berjalan dengan lancar dan kita
mendapat pakej Python_ yang diperlukan. Navigasi ke dalam ``My Computer`` anda
ke lokasi berikut - ``C:\Python\Portable Python 2.7.3.1``. Pastikan *folder*
tersebut mempunyai folder dan fail-fail seperti dalam cekupan skrin di bawah:- 

.. image:: ../images/portable-dir.png
    :align: center
    :scale: 70%

Klik dua kali pada fail ``Portable-Python`` untuk melancarkannya dan anda akan
mendapat skrin konsol Python.

.. image:: ../images/pyterm.png
    :align: center
    :scale: 70%

Taip kod berikut dalam konsol berkenaan::

    >>> import django
    >>> django

Anda akan mendapat output seperti berikut::

    <module 'django' from 'C:\Python\Portable Python 2.7.3.1\App\lib\site-packages\django\__init__.pyc'>

.. image:: ../images/pyterm-2.png
    :align: center
    :scale: 70%

Tahniah ! Ini menunjukkan anda telah berjaya meng'*install*' sistem Python ke dalam komputer anda. Anda sekarang sudah bersedia untuk mula mempelajari Django.

.. _Django: http://www.djangoproject.org/
.. _Python: http://www.python.org/
.. _PortablePython: http://www.portablepython.com/
.. _Notepad++: http://notepad-plus-plus.org/
