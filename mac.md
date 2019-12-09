# Mac 常用终端命令

### 目录操作

创建一个名为foo的目录

```
mkdir foo
```



进入目录foo

```
cd foo
```



删除目录 foo

```
rmdir foo
```



删除目录 foo和它的子目录、文件

```
rm -rf foo
```



目录eoo重命名为 foo,  ./ 代表相对路径，指当前目录

```
mv ./eoo foo
```



把目录foo和它的子目录、文件一起移动到 eoo 目录下

```
mv ./foo ./eoo
```



显示当前目录的内容

```
ls
```



显示当前目录的详细内容

```
ls -la
```



###文件操作

创建文件名称为readme，后缀名为.md 

```
touch readme.md
```



查看readme文件

```
cat readme.md
```



复制文件或者目录,复制 foo.txt 到 foo1.txt

```
cp ./foo.txt ./foo1.txt
```



打开文件或者目录,打开readme.md

```
open readme.md
```



打开当前目录

```
open .
```



### 选择操作

显示readme.md前5行

```
head -5 readme.md
```



显示readme.md后5行

```
tail -5 readme.md
```



在文件readme.md 中查找含有 “hello”

```
grep 'hello' readme.md
```

