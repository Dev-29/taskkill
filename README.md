# taskkill
custom AV bypass rev shell script
# compile
i686-w64-mingw32-g++ taskkill.cpp -o taskkill.exe -lws2_32 -s -ffunction-sections -fdata-sections -Wno-write-strings -fno-exceptions -fmerge-all-constants -static-libstdc++ -static-libgcc
