# mark meshsegnet data
基于MeshsegNet的标注工具的灵感，新构建了三维齿科的标注工具.

# 背景：
由于多种原因，迟迟没有上传到自己的仓库；因此在github上已经有了一版开源的代码，其实当时是我们一起完成的，不过以前不懂事，外加淡泊名利等等，也有点自恃清高
等等;于是并没有意识到其严重性，说起来，都是眼泪... 


# 环境配置：

- 1. 使用前 先进行vtk的编译，当时使用的是 8.2
- 2. qt 使用的版本 是5.12 ， 不过我想应该是兼容之前的环境的
- 3. 编译完成之后，注意配置vtk的环境 ，配置 include目录 以及lib 目录，这个网络上的教程很多，基本上在编译vtk之后都有相关的操作
- 备注：注意修改文件路径！！！

# 文件目录解释：
- 1. vtk 文件夹内 
    - designInteractorStyle  鼠标交互/点选拾取
    - vktshow 主界面显示 / 文件操作
- 2. UI 文件夹内
    - colortablewidget 色卡
    - mytablewidget 其他作者

# 演示视频：
- 小对比一下，当然了,向大佬学习，站在巨人的肩膀上 [Mesh_Labeler](https://github.com/Tai-Hsien/Mesh_Labeler)
![mp4:](./软件演示.mp4)

