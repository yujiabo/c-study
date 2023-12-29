- 清屏命令

  ```
  clear   //快捷键  ctrl + l
  ```

- 查看当前路径

  ```
  pwd    // print working dir
  ```

- cd命令

  > cd  绝对路径或相对路径进入指定目录

  ```
  cd /home/bin
  ```

  > cd ~或回车   返回主目录

  ```
  cd ~
  ```

- ls命令查看目录内容

  > ls  目录路径

  ```
  ls /home/bin
  ```

  > 查看当前目录下所有内容包括隐藏文件

  ```
  ls -a
  ```

  > 查看当前目录下所文件详细信息

  ```
  ls -l  或者  ls -al
  ```


- touch 创建空文件

  > touch  文件路径

  ```
  touch  /home/a.txt
  ```

- mkdir 创建空目录

  > mkdir 目录路径  

  ```
  mkdir /home/test
  ```

  > 逐级创建指定目录
  >
  > mkdir 目录路径 -p

  ```
  mkdir /home/a/b/c -p
  ```

- rm 删除命令

  > 删除文件
  >
  > rm 文件名  

  ```
  rm a.txt
  ```

  > 删除目录
  >
  > rm 目录名 -fr

  ```
  rm test -fr
  ```

- cp 拷贝命令

  > 拷贝文件
  >
  > cp   源文件   目标文件

  ````
  cp hello.c world.c  //将hello.c拷贝一份到当前目录下，新文件名为world.c
  ````

  > 拷贝目录
  >
  > cp   源目录  目标目录  -fr

  ```
  cp  test  test1  -fr
  ```

  

- cat  快速查看文件内容

  > cat  文件名

  ```
  cat a.txt
  ```

  