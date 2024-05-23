# 自定义着色器

若内置的着色器无法满足需求，可通过自定义着色器实现特例化渲染。

自定义着色器有以下两种方式：

1. 参考 [着色器资源](./effect-inspector.md) 创建新的着色器。

2. 基于内置着色器。将 **资源管理器** 面板中 **internal/effects/** 目录下相应的内置着色器拷贝到 **assets** 目录下，然后对其进行自定义。

## 准备工作

由于着色器是使用 YAML 作为流程控制，GLSL 作为着色器语言，因此在自定义着色器之前需要对这些知识有一定程度上的熟悉和了解：

对于不熟悉的开发者，我们也准备了一些简单的介绍：

- [GLSL 语法简介](./glsl.md)
- [YAML 语法简介](./yaml-101.md)

本节将以自定义 2D 着色器和 3D 着色器为例，详细介绍自定义流程，具体内容请参考：

- [3D 着色器：RimLight](write-effect-3d-rim-light.md)
- [2D 着色器：Gradient](write-effect-2d-sprite-gradient.md)