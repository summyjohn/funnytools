# funnytools
用python写的小工具

## 01. 目录文件分类
   ### 前言：
        有时候，想要对一个目录里的文件进行搜索或者分类操作往往是一件痛苦的事情，下面这个程序的目的是将目录下的文件树以某种分类规则进行排列。
   ### 用法：
        usage: classify.py [-h] [-t {ext,mtime,back}] directory
        对目录进行文件整理归类.
        positional arguments:
          directory             目标目录路径
        optional arguments:
          -h, --help            show this help message and exit
          -t {ext,mtime,back}, --type {ext,mtime,back}
                                分类方式
       按扩展名分类:
         python classify.py -t ext 目录路径
    ### 效果：
        ├── DS_Store
        ├── bat
        ├── bin
        ├── css
        ├── db
        ├── default
        ├── gif
        ├── gitattributes
        ├── gitignore
        ├── htaccess
        ├── jar
        ├── js
        ├── json
        ├── lib
        ├── log
        ├── md
        ├── php
        ├── plex
        ├── png
        ├── sql
        ├── sublime-project
        ├── sublime-workspace
        ├── tpl
        ├── txt
        ├── xml
        ├── y
        └── yml
