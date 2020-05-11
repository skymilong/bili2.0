更新打包放蓝奏云了：https://skymilong.lanzous.com/ichpekd


作者代码中有很多本包内文件引用，使用的 from . import xxx的方式。
然而打包会出现module "__main__" not found的问题。
建议在文件夹中__init__.py的文件，并且修改代码，使用 from 包名 import xxx 引入包

需要自己打包的，只需修改前面的问题即可正常打包。打包多文件项目需要配置.spec文件,建议百度看看。
