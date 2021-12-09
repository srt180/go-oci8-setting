## go oci8 settings in Windows10.x86_64

# gcc
C:\app\mingw-w64\x86_64-5.3.0-posix-seh-rt_v4-rev0\mingw64\bin\gcc.exe

# oci client
Client Shared Library 64-bit - 21.3.0.0.0

# go version
go version go1.17.2 windows/amd64

# pkg-config
version: 0.28

# env 
PATH:

C:\app\mingw-w64\x86_64-5.3.0-posix-seh-rt_v4-rev0\mingw64\bin;

C:\instantclient_21_3

# oci8.pc
```
gcc=C:/app/mingw-w64/x86_64-5.3.0-posix-seh-rt_v4-rev0/mingw64

oralib=C:/instantclient_21_3/sdk/lib/msvc
orainclude=C:/instantclient_21_3/sdk/include

gcclib=C:/app/mingw-w64/x86_64-5.3.0-posix-seh-rt_v4-rev0/mingw64/lib
gccinclude=C:/app/mingw-w64/x86_64-5.3.0-posix-seh-rt_v4-rev0/mingw64/include

Name: OCI
Description: Oracle database engine
Version: 21.3
Libs: -L${oralib} -L${gcclib} -loci
Libs.private: 
Cflags: -I${orainclude} -I${gccinclude}
```

# WARNING
put pkg-config.exe binary into gcc path
