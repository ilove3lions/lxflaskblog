# 基于flask的博客系统搭建

- 安装数据库迁移。输入以下命令
  * `python manager.py db init` (使用init命令创建迁移仓库)
  * `python manager.py db migrate -m "initial migration"`(migrate命令用来自动创建迁移脚本)
  * `python manager.py db upgrade`(更新数据库，第一次使用该命令会新建一个数据库，可以利用pycharm右侧的Database查看该数据库)
- 7.部署程序，`python manager.py deploy`
- 8.在本地运行程序,`python manager.py runserver`打开http://127.0.0.1:5000端口查看, 按Ctrl+C退出程序。


