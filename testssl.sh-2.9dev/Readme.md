Menguji Keamanan Enkripsi SSL dengan Testssl.sh - Kali ini saya akan sharing salahsatu tool yang bisa membantu kalian untuk menguji SSL yang terpasang di server. Testssl.sh adalah tool yang dikembangkan dengan bahasa pemrograman bash dan digunakan untuk menguji SSL. Dengan testssl.sh, kalian bisa mengecek apakah ada kesalahan konfigurasi yang menyebabkan bug, menguji koneksi HTTPS dengan simulasi dari beberapa device berbeda, dan masih banyak fitur lain.


Berikut fitur utama dari testssl.sh
++++++++++++++++++++++++++++++++++++++
- Clear output: you can tell easily whether anything is good or bad
- Ease of installation: It works for Linux, OSX/Darwin, FreeBSD, NetBSD, OpenBSD (needs bash) and MSYS2/Cygwin out of the box: no need to   install or to configure something. No gems, CPAN, pip or the like/
- Flexibility: You can test any SSL/TLS enabled and STARTTLS service, not only webservers at port 443
- Toolbox: Several command line options help you to run YOUR test and configure YOUR output
- Reliability: features are tested thoroughly
- Verbosity: If a particular check cannot be performed because of a missing capability on your client side, you'll get a warning
- Privacy: It's only you who sees the result, not a third party
- Freedom: It's 100% open source. You can look at the code, see what's going on and you can change it.
- Heck, even the development is open (github)
+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
Cara Install
Caranya cukup mudah. Tapi sebelum itu pastikan dependensinya sudah terinstall:
+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
openssl
git
+++++++++++++++
Download testssl.sh nya, lalu :
+++++++++++++++++++++++++++++++++++++++++++++++++++++++++
./testssl.sh https://domain.com
+++++++++++++++++++++++++++++++++++++++++++++++++++++++++
Namun kalian juga bisa mendapatkan hasil yang lebih rinci dengan menggunakan beberapa perintah yang tersedia. Bisa dicek dengan perintah :
++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
./testssl.sh --help
