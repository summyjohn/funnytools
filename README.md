# funnytools
用python写的小工具

*01. 目录文件分类<br/>
   *前言：<br/>
        有时候，想要对一个目录里的文件进行搜索或者分类操作往往是一件痛苦的事情，下面这个程序的目的是将目录下的文件树以某种分类规则进行排列。<br/>
   *用法：<br/>
        `usage: classify.py [-h] [-t {ext,mtime,back}] directory`<br/>
        对目录进行文件整理归类.<br/>
       ` positional arguments:`<br/>
          directory             目标目录路径<br/>
        `optional arguments:<br/>
          -h, --help            show this help message and exit<br/>
          -t {ext,mtime,back}, --type {ext,mtime,back}`<br/>
                                分类方式<br/>
       按扩展名分类:<br/>
        ` python classify.py -t ext `目录路径<br/>
    *效果：
        ├── DS_Store <br/>
        ├── bat<br/>
        ├── bin<br/>
        ├── css<br/>
        ├── db<br/>
        ├── default<br/>
        ├── gif<br/>
        ├── gitattributes<br/>
        ├── gitignore<br/>
        ├── htaccess<br/>
        ├── jar<br/>
        ├── js<br/>
        ├── json<br/>
        ├── lib<br/>
        ├── log<br/>
        ├── md<br/>
        ├── php<br/>
        ├── plex<br/>
        ├── png<br/>
        ├── sql<br/>
        ├── sublime-project<br/>
        ├── sublime-workspace<br/>
        ├── tpl<br/>
        ├── txt<br/>
        ├── xml<br/>
        ├── y<br/>
        └── yml<br/>
