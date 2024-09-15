# 通过微调使得模型符合需求，构建属于自身的AI


安装环境后，报错
~~~


A module that was compiled using NumPy 1.x cannot be run in
NumPy 2.0.1 as it may crash. To support both 1.x and 2.x
versions of NumPy, modules must be compiled with NumPy 2.0.
Some module may need to rebuild instead e.g. with 'pybind11>=2.12'.

If you are a user of the module, the easiest solution will be to
downgrade to 'numpy<2' or try to upgrade the affected module.
We expect that some modules will need time to support NumPy 2.

提示numpy版本过高

solution: pip install numpy==1.26.4

~~~


## fine-tune前
![微调前](./img/ft_before.png)

属于上海人工智能实验室的AI助手