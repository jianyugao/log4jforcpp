# log4jforcpp
Complie log4c and JNI togehter:

gcc -shared  -fPIC  -L/usr/local/log4c/lib/ -I$JAVA_HOME/include -I$JAVA_HOME/include/linux  -I/usr/local/log4c/include /usr/local/log4c/lib/liblog4c.so HelloJNI.c  log.c -o libReadFile.so -llog4c

File needed when deploy log4c

log.c log.h log4c(folder) log4crc log4c.h  
log4c version is:log4c-1.2.4

Automatically exported from code.google.com/p/log4jforcpp
