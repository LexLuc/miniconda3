.. conda_note documentation master file, created by
   sphinx-quickstart on Sat Mar  3 20:44:02 2018.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

==============
Conda 学习笔记
==============

|

:emphasis:`用于任何语言 (Python，R，Ruby，Lua，Scala，Java，JavaScript，
C / C ++，FORTRAN) 的包 (package)，依赖 (dependency) 和环境 (environment)`


简介
====

Conda是一个在Windows，MacOS和Linux上运行的开源软件包管理系统和环境管理系统。 
Conda可以快速安装，运行和更新软件包及其依赖项。 Conda可轻松创建，保存，加载
和切换本地计算机上的环境。它是为Python程序创建的，但它可以打包并分发任何语言的软件。

Conda作为软件包管理员可以帮助查找和安装软件包。如果你需要一个需要不同版本的Python软件包，
你不需要切换到不同的环境管理器，因为conda也是一个环境管理器。只需几条命令，就可以
设置完全独立的环境来运行不同版本的Python，同时继续在正常环境中运行常用版本的Python。

在其默认配置中，conda可以安装和管理由Anaconda构建，审查和维护的repo.continuum.io上的
一千个软件包。

Conda可以与持续集成系统（如Travis CI和AppVeyor）相结合，为代码提供自动化测试。

conda包和环境管理器包含在以下所有版本中:

:ref:`Anaconda <anaconda-glossary>`\ |co|

:ref:`Miniconda <miniconda-glossary>`

`Anaconda Repository <https://docs.continuum.io/anaconda-repository/>`_

Conda也包含在 `Anaconda Enterprise <https://www.anaconda.com/enterprise/>`_  中，
它为Python，R，Node.js，Java和其他应用程序栈提供现场企业软件包和环境管理。 
Conda同样可以在PyPI上使用，尽管这种方法可能不是最新的。

.. toctree::
   :hidden:
   :maxdepth: 1
   :caption: 目录:
   :numbered:
   
   user-guide/index
   help-support
   release-notes
   commands
   glossary
   licence

.. |co|    unicode:: U+000AE .. REGISTERED SIGN

索引表
======

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
