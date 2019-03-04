```python 
 # 创建文件夹
   mkdir [文件名]
 # 创建项目
   django-admin startproject main [文件名]
 # 进入项目目录
   cd [文件名]
 #　数据迁移（创建，修改数据表）
   python manage.py migrate
 # 创建超级管理员账号（admin/admin@123）
   python manage.py createsuperuser
 # 启动web服务器
   python manage.py runserver 127.0.0.1:8282
```