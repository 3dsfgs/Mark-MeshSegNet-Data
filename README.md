
# Language

- [English](#english)
- [中文](#中文)

# 中文
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
    - vtkshow 主界面显示 / 文件操作
- 2. UI 文件夹内
    - colortablewidget 色卡
    - mytablewidget 其他作者

# 演示视频：
    - 小对比一下，当然了,向大佬学习，站在巨人的肩膀上
[Mesh_Labeler](https://github.com/Tai-Hsien/Mesh_Labeler)
    [mp4:](./软件演示.mp4)

## 备注: demo 演示视频 可以下载 查看 


# English
## mark-meshsegnet-data

A 3D dental annotation tool inspired by MeshSegNet labeling framework.

## Background
For various reasons, I delayed uploading this project to my personal repository. There is already an open-source version of the code published on GitHub, which was actually developed collaboratively by our team. Back then, I was immature, cared little about credit, and held an arrogant attitude. I failed to recognize the severity of this issue at the time. Looking back, it is quite regretful.
## Environment Setup
    Compile VTK beforehand; version 8.2 was used during development.
    Qt 5.12 is adopted, and backward compatibility with older Qt versions is expected.
    After compilation, properly configure VTK environment variables, including header include directories and library lib directories. Plenty of online tutorials cover this setup procedure post VTK compilation.
    Note: Remember to update all file paths accordingly!!!
## Directory Structure Explanation
### vtk folder
    designInteractorStyle: Mouse interaction and point picking logic
    vtkshow: Main view rendering and file I/O operations
### UI folder
    colortablewidget: Color palette component
    mytablewidget: Components referenced from other open-source works
## Demo Video
This project draws inspiration from existing excellent implementations, standing on the shoulders of predecessors. Special reference: Mesh_Labeler

## Note: The demo demonstration video can be downloaded and viewed
-![mp4:](./软件演示.mp4)

