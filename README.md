
参考：https://github.com/XieGuochao/csapp

环境(Docker image)：https://hub.docker.com/r/xieguochao/csapp

使用方法：

1. 获取源码：git clone github.com/tang1heng/csapp
2. 移动到工作目录下：cd csapp
3. 修改文件夹访问权限：sudo chmod -R a+rwx ./labs
4. 运行 docker 容器：docker run -p 7777:7777 -v "$PWD/labs:/home/csapp/project" csapp
5. 使用密码 csapp 访问 http://localhost:7777/
