## 项目骨架

## 项目骨架

说明如下：

```
.
├── config-example.py               // 配置文件样例
├── docs                            // 所有doc文件放到该目录
│   └── README.md
├── LICENSE
├── README.md
├── install                         // 安装说明
├── dashboard
│   └── assets                     // app目录
│   │   ├── admin.py
│   │   ├── apps.py               // 新版本django app设置文件
│   │   ├── api.py                // api文件
│   │   ├── __init__.py
│   │   ├── migrations            // models Migrations版本控制目录
│   │       └── __init__.py
│   │   ├── models.py             // 数据模型目录
│   │   ├── static                // app下静态资源目录
│   │   │   └── assets           // 多一层目录，防止资源重名
│   │   │        └── some_image.png
│   │   ├── templates             // app下模板目录
│   │       └── assets            // 多一层目录，防止资源重名
│   │           └── asset_list.html
│   │   ├── templatetags          // 模板标签目录
│   │   ├── tests.py              // 测试用例文件
│   │   ├── urls.py               // urlconf文件
│   │   └── views.py              // views文件
│   ├── jumpserver                 // 项目设置目录
│   │    ├── __init__.py
│   │    ├── settings.py          // 项目设置文件
│   │    ├── urls.py              // 项目入口urlconf
│   │    └── wsgi.py
│   ├── manage.py
│   ├── static                    // 项目静态资源目录
│   └── templates                 // 项目模板目录
```