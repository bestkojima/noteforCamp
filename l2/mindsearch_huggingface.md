在部署过程中出现报错

~~~ python
ImportError: cannot import name 'AutoRegister' from 'class_registry' (/usr/local/lib/python3.10/site-packages/class_registry/__init__.py)
~~~


pip show class_registry 查看版本
在 requirement 文件 中添加 class_registry==2.1.2


之后部署成功了
![](./img/final.png)

link: https://huggingface.co/spaces/atom2individual/mindsearch_test