
# 命令

## 循环

``` c

循环
for /l %x in (1, 1, 100) do echo hello%x

创建文件
fsutil file createnew C:\file\cc.txt

循环创建文件
for /L %i in (10001,2,20000) do fsutil file createnew C:\file\%i.txt 10485760


for /L %i in (10002,2,20000) do fsutil file createnew C:\file\%i.txt 10240

```

### 参考文件

``` a


```

## perl编译

``` 64bit
perl Configure VC-WIN64A shared no-asm --prefix="C:/Users/Administrator/Desktop/make1/64/openssl-1.1.1e/win64-release" --openssldir="C:/Users/Administrator/Desktop/make1/64/openssl-1.1.1e/win64-release/ssl"
nmake
nmake install
```

```32bit
perl Configure VC-WIN32 shared no-asm --prefix="C:/Users/Administrator/Desktop/openssl-1.1.1e/win32-release" --openssldir="C:/Users/Administrator/Desktop/openssl-1.1.1e/win32-release/ssl"
nmake
nmake install
```

## nmake编译

``` x64 vs2005需要安装64bit的支持软件
    nmake /f Makefile.vc mode=static VC=8 MACHINE=x64
```

``` x86
    nmake /f Makefile.vc mode=static VC=8 MACHINE=x86
```

### 编译必要条件

``` vs2005
 在vs2005的特定命令行 32bit或64bit编译
```

``` vs2012
 在vs2012的命令行 编译
```
