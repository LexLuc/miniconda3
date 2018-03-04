========
安装教程
========

.. contents::
   :local:
   :depth: 2

:doc:`获取 <download>` conda 的最快方法是安装     .. 跳转到toctree对应条目所指定的内容
mini版本：:ref:`Miniconda <miniconda-glossary>`， .. 跳转到相同文档指定页面中指定的位置
该版本仅包含 conda 及其依赖。如果你有充裕的时间（一小时左右）
和硬盘空间（3GB以上），并且需要一次性安装超过720个开源包，
请安装完整版 Anaconda。

官方建议安装 Anaconda for local user，因为它是
最稳定的安装方法且不需要管理员权限；
而安装 Anaconda system wide 是需要管理员权限的。

如果想在 Windows 或 Mac 系统使用图形化的安装工具，
可以参考 `图形化安装教程 <http://docs.continuum.io/anaconda/install.html>`_。


系统要求
========

* Miniconda 需要的硬盘空间 —— 400MB及以上
* Anaconda 需要的磁盘空间 —— 3GB及以上
* 操作系统为32/64位的Windows/Mac/Linux


普通安装
========

选择操作系统：

* :doc:`Windows <regular-install-win>`
* :doc:`Mac <regular-install-mac>`
* :doc:`Linux <regular-install-linux>`


静默模式安装
============

使用静默模式安装 Miniconda 或 Anaconda 来部署/测试/构建服务，
如 Travis CI 和 AppVeyor。

选择操作系统：

* :doc:`Windows <silent-install-win>`
* :doc:`Mac <silent-install-mac>`
* :doc:`Linux <silent-install-linux>`


在已经安装python及附带库的机器上安装
=================================

无需卸载电脑上原有的 Python 环境，安装步骤大致与普通安装相同，
额外需要做的只有将 Python 的 conda 添加到 PATH 环境，无需设置 
PYTHONPATH 环境变量。

检查 conda 是否成功添加到系统 PATH 变量
--------------------------------------------------------

* Mac 和 Linux 系统打开 terminal 并输入``echo $PATH``
* Windows 系统打开 cmd 并输入 ``echo %PATH%``

查看哪个 Python 被设为默认应用
-------------------------------------------

* Mac 和 Linux 系统打开 terminal 并输入``which python``
* Windows 系统打开 cmd 并输入 ``where python``

查看当前 conda 环境已安装库及对应版本
-----------------------------------------------------

打开 terminal/cmd，运行命令 `conda list`

.. toctree::
   :maxdepth: 1
   :hidden:           .. 该 toctree 的内容不显示在页面中
   
   download
   regular-install-win
   regular-install-mac
   regular-install-linux
   test-installation
