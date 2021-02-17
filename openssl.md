# Cross Compiling OpenSSL

```
sudo apt install gcc-9-arm-linux-gnueabihf g++-9-arm-linux-gnueabihf
./Configure linux-armv4 --prefix=/dev/shm/openssl --openssldir=/dev/shm/openssl shared
make CC=arm-linux-gnueabihf-gcc-9
```

