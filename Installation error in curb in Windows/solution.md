
Download libcurl. (Files provided in repository) url: http://curl.haxx.se/gknw.net/7.40.0/dist-w32/renamed-curl-7.40.0-devel-mingw32.zip

To make SSL certification work, set environment variable

CURL_CA_BUNDLE=C:\Ruby200\bin\ca-bundle.crt
SSL_CERT_FILE=C:\Ruby200\bin\cacert.pem

copy all DLL and EXE file in C:\curl-7.40.0-devel-mingw32\bin to C:\Ruby200\bin

Run:

gem install curb --platform=ruby -- --with-curl-lib=C:/curl-7.40.0-devel-mingw32/bin --with-curl-include=C:/curl-7.40.0-devel-mingw32/include

