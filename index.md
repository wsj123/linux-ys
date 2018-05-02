## 基本压缩命令

.zip   .rar .bz2 

```markdown

基本压缩命令
zip 压缩文件名  源文件


zip -r 压缩文件名  源目录


ls

zip longzls.zip longzls


linux不区分扩展名


压缩格式做换算


mkdir jp

ls


touch jp/cangls 

touch jp/longls

touch jp/boduols

zip -r jp.zip jp

unzip 解压缩

rm -rf jp

ls
unzip longls.zip


gzip 源文件  .gz

gzip -c 源文件 > 压缩文件

gzip -r 目录

rm -rf "*.zip"


gzip longzls

ls > abc

cat abc


gzip -c abc 

gzip -c abc > abc.gz 源文件不消失


gzip jp


gzip -r jp 压缩子目录


gzip -d 压缩文件 解压缩

gunzip  longzls.zip

gunzip -r jp


bzip2 源文件


bzip2 -k 源文件，不能压缩目录


bzip2 abc

bzip2 -k longzls 压缩文件保存源目录


bzip2  -d abc.bz2
```
