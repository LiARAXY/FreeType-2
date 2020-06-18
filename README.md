# FreeType-2
> Download from https://www.freetype.org/



# Download URL

> https://sourceforge.net/projects/freetype/files/freetype2/



# Cross Compiler

> ./configure --prefix=/usr/local/freetype2  --host=arm-linux CC=arm-linux-gnueabihf-gcc --enable-shared --enable-static --with-zlib=no --with-bzip2=no --with-png=no --with-harfbuzz=no 
>
> make && make install

- –prefix：指定安装目录

- –host：指定目标主机类型

- CC：指定交叉编译工具

- –enable-shared：编译生成.so动态库

- –enable-static：编译生成.a静态库

- 不使用zlib、bzip2、png、harfbuzz

  