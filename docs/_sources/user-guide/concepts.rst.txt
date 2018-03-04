======
概念
======

.. contents::
   :local:
   :depth: 1

conda 的目录结构
=================

**ROOT_DIR**

Anaconda 或 Miniconda 所安装的目录

例如：

.. code-block:: none

   /opt/Anaconda
   C:\Miniconda

   
**/pkgs**

该目录包含解压后用于 conda 环境的包，每个包都存于对应的子目录下。
同 **PKGS_DIR**。

**/envs**

conda 环境所存放的位置。

默认的 conda 环境由以下子目录组成：

| ``/bin``
| ``/include``
| ``/lib``
| ``/share``
|


conda 环境
============

conda 环境是一个包含了已安装特定 conda 包的目录。
例如，你可能有一个NumPy 1.7和它的环境
依赖，和另一个与NumPy 1.6兼容的环境
测试。 如果你改变一个环境，你的其他环境
不受影响，仅仅通过激活或停用环境来完成切换。 
如果需要分享 conda 环境，只要提供一份
``environment.yaml``文件即可。

https://github.com/conda/conda-docs/edit/master/docs/source/user-guide/concepts.rst