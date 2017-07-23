# how-to-gitignore

## 1. 哪些文件不应该放在.gitignore文件中？</br>
* 所有的.idea文件夹中的文件都不应该放在.gitignore文件中，除过workspace.xml和task.xml
* .iml 文件（普通工程）
* .iws文件

## 2. 哪些文件应该放在.gitignore文件中？</br>
*  Gradle和Maven项目中的.iml文件
* gradle.xml
* idea/libraries 文件下的xml文件

对于哪些文件该放入.gitignore哪些文件不该放入.gitignore,可以参考如下链接：https://intellij-support.jetbrains.com/hc/en-us/articles/206544839-How-to-manage-projects-under-Version-Control-Systems   </br>
## 3. 将文件放入.gitignore文件 </br>
* 方法1</br>
``` echo  文件名  >> .gitignore  ```
实际上，是在.gitignore文件中添加了一条
* 方法2</br>
 在[https://www.gitignore.io/](https://www.gitignore.io/) 中生成对应的.gitignore文件，拷贝生成.gitignore文件对应的URL，运行如下命令
```curl   URL  >> .gitignore ```
