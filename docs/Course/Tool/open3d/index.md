# Open3D: A Modern Library for 3D Data Processing

标题如上，敢于自称“现代”，其必须要有现代的优点，个人总结如下：

- 功能齐全：不仅包含 Legacy Software 的全部功能，还应该包含适应新的需求的功能
- 数据格式支持广泛，甚至支持自定义格式（前提是自己写扩展
- 良好的语言支持：支持一种编译语言和一种脚本语言，这属于易用性方面
- 清晰的文档、面向对象的封装：支持哪些模块，都要分得明白
- 函数名清楚明了：不要再为了在 CRT 荧幕上少敲几个字而缩略了
- 底层代码模块分明、逻辑清晰
- 例程丰富（哪个程序不是例程改出来的

> 不是说 MATLAB 不好，可是，除了特定领域，如数学研究以外，研究人员在大量地使用 Python，所以对 Python 的良好支持可以说是必要的

没错，Open3D 就是一个拥有以上全部特性的三维库。

当然，也不得不说其缺点，就是依赖多，甚至依赖了`Jupyter`。虽然这说明了`open3d.visualization`支持`Jupyter`，但如果没有在`Jupyter notebook`中运行的需求的话，这一部分空间占用实在是鸡肋。
