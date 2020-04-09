### 设置模块搜索路径的方式
1) 设置PYTHONPATH环境变量
   1) linux 下 ~./profile
   2) pycharm 下 configure
2) 添加.pth文件
   1) 在lib/site-package 里面，将写好的python脚本写成.pth文件，就可以作为系统包导入。
3) 通过sys.path设置路径
   ```
   import sys
   sys.path.append(文件夹路径)
   ```