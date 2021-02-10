#phpmyadmin perlu sedikit di optimasi agar lebih aman.
#kopi file nginx.conf ke direktori /etc pada image phpmyadmin:latest
#beri nama image yang baru menjadi phpmyadmin-custom
FROM phpmyadmin:latest

LABEL maintainer="<amuyassar16@gmail.com>" 

COPY nginx.conf /etc/nginx/conf

