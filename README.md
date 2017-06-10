https://zhuanlan.zhihu.com/p/27158983
知乎持续更新，以知乎为准


不同于目前互联网上经常见到的书单推荐，本文侧重收集、整理图形学研究所需要的各个方面（基础知识，领域重要著作，工具链参考手册）以供想了解/快速上手该细分领域的同学参考。

本书单长期更新，请在评论区中留下您的反馈意见/补充推荐，我们会定期对这个书单做更新。



由于编者水平有限，难免有遗漏和不妥之处，请各位客官不吝赐教。

Contributors：@硕鼠酱 ，@李旻辰 ，@Raymond

方向

### Introduction
![](https://images-na.ssl-images-amazon.com/images/I/51mG5L1RaTL._SX359_BO1,204,203,200_.jpg)
> Interactive computer graphics : a top-down approach with shader-based OpenGL / Edward Angel et al.

相当不错的图形学入门读物，偏重实时渲染。用OpenGL（新版本为WebGL）作为教学，简单容易上手。

![](https://images-na.ssl-images-amazon.com/images/I/51u+sv0N2EL._SX258_BO1,204,203,200_.jpg)
>  The Art of 3D Computer Animation and Effects by Isaac V. Kerlow

全面介绍电影/动画工业的方方面面，由迪斯尼工作人员攒书，值得一看。

### Geometry Processing
![enter image description here](https://images-na.ssl-images-amazon.com/images/I/515vlgbdXjL._SX397_BO1,204,203,200_.jpg)
> Computational Geometry: Algorithms and Applications. Third Edition. Mark de Berg, et al

计算几何经典之作，深入浅出，例子很多，每一章开头都有本章内容的实际应用，书后附有大量习题。

![](https://images-na.ssl-images-amazon.com/images/I/51WzvDvGrEL.jpg)
>Polygon mesh processing. CRC press. Botsch et al. 2010

包括基本的几何形体处理算法的讲解，比如平滑降噪、参数化、三角剖分、简化与近似、形变等。

![](https://www.cs.cmu.edu/~kmcrane/Projects/DDG/preview.png)
>Discrete Differential Geometry: An Applied Introduction. Keenan Crane 2015

讲述传统微分几何的基本概念如何在离散计算中得到应用，同时也会涉及到对一些相关数学工具的应用的探讨。内容主要包括曲率、平行转移、外蕴代数和微积分、拓扑、霍奇分解、保角映射、有限元方法等。

![](http://fernandodegoes.org/figures/vfSig16.jpg)
>Vector Field Processing on Triangle Meshes. Fernando de Goes et al. 2015

讲述如何在几何体表面的切空间定义向量场并应用到对几何形体的处理中。本文也着重讲解了如何将传统微分几何的概念离散化到三角形网格上，选取三角形、顶点、边作为离散元分别有何优缺点。

### Rendering
![](https://images-na.ssl-images-amazon.com/images/I/81t7zJQiEiL.jpg)
>Physically Based Rendering, From Theory to Implementation /Matt Pharr

讲解详细体系完备，更难能可贵的是本书配套一个渲染系统，书后习题提供了参考文献和思路来改进这个渲染系统，学练结合，夫复何求？

![](http://www.realtimerendering.com/rtr3.jpg)
>Real-Time Rendering, Tomas Akenine-Moller, Eric Haines & Naty Hoffman

与离线渲染相对应的实时渲染经典著作，针对现代图形渲染管线、GPU、着色器等有详细讲解。同时总结了大量游戏开发中非常实用的算法。

### Simulation and Animation

![](https://images-na.ssl-images-amazon.com/images/I/51Y+Alb5S-L._SX335_BO1,204,203,200_.jpg)
> Fluid simulation for computer graphics / Robert Bridson

作者流体模拟届大牛Bridson，从NS方程的推导入手，详细介绍流体模拟的经典算法，是做物理模拟方向的同学几乎人手一本的参考书。

![](https://images-na.ssl-images-amazon.com/images/I/41hdIY4ecAL._SX348_BO1,204,203,200_.jpg)
> Nonlinear Continuum Mechanics for Finite Element Analysis / Javier Bonet & Richard D. Wood

固体、软体模拟、声音合成等方向的必读物。从最简单的线性机械学介绍到非线性机械学，对各种应力模型都有详细的介绍。同时对不同机械学模型的有限元分析也进行了深入的讲解。

![](https://images.springer.com/sgw/books/medium/9783540680925.jpg)
> Boundary Element Method / Stefan A. Sauter & Christoph Schwab

本书详细介绍了边界元方法的理论和具体的数值方法。从边界元的概念、伽辽金方法等，讲述到椭圆边界积分方程的性质和解法，之后详细介绍了边界元方法及其在不同应用下的各种变通方法，最后也介绍了一些相关的线性方程求解和误差分析方法。

![](http://images.slideplayer.com/16/4932981/slides/slide_6.jpg)
> Rigid Body Simulation I & II / David Baraff

刚体模拟的入门读物，从最基本的刚体运动方程讲到刚体碰撞等。作者是皮克斯动画工作室的高级研究员，其开发的布料模拟算法已被广泛采纳于各种游戏和特效引擎中。





### Mathematics 
本分类收集边角料

![](https://images-na.ssl-images-amazon.com/images/I/51YG5fKzL6L._SX310_BO1,204,203,200_.jpg)
> Linear Algebra and Its Applications / Peter Lax

作者是科学计算领域大家，这本书用分析的视角介绍了线性代数/ 数值线性代数的方方面面，适合有本科数学基础的同学参考。

![](https://static-content.springer.com/cover/book/978-3-662-09017-6.jpg)
> Numerical  Solution of  Time-Dependent Advection-Diffusion-Reaction  Equations / Willem Hundsdorfer and Jan Verwer

从Method of Lines讲解抛物方程数值求解的一本观点新颖的著作，可供做流体模拟/CFD的同学参考。

![](https://images-na.ssl-images-amazon.com/images/I/51YEzxaWu2L._SX400_BO1,204,203,200_.jpg)
>  Numerical Mathematics and Computing / Cheney, E., and David Kincaid.

一本比较新的计算数学著作，详细介绍了科学计算各个方面，知识比较新，并有详细的例子。

![](https://images-na.ssl-images-amazon.com/images/I/51GSFfdn5LL._SY344_BO1,204,203,200_.jpg)
> Modern Mathematics and Applications in Computer Graphics and Vision / Hongyu Guo

这本书收集了很多计算机图形学和视觉科学需要用到的现代数学知识。

![enter image description here](http://users.iems.northwestern.edu/~nocedal/images/cover-m.gif)
> Numerical Optimization / Jorge Nocedal & Stephen J. Wright

数值优化的经典著作，作者是开发了著名非线性优化算法L-BFGS的大牛，和数值计算相关领域的必读书目。

![enter image description here](https://images-na.ssl-images-amazon.com/images/I/41YYrZL9nsL._SX330_BO1,204,203,200_.jpg)
> Partial Differential Equations / L. C. Evans

本书从应用角度全面地介绍了偏微分方程的相关内容，结合经典的工科应用，详细讲述了偏微分方程的类型、求解方法以及相关理论，适合已有数学分析基础的同学学习。

![](https://img3.doubanio.com/lpic/s1525451.jpg)
> 微积分学教程(三卷本) / 菲赫今哥尔茨

这套书是享誉世界的著作。然而由于体量实在太大，所以更适合作为参考资料使用。这套书讲解相当详细，每一章几乎都可以自成体系，并且配备数量可观的例题，是快速回忆微积分相关公式/定理绝佳的参考资料。

### Toolchain

![](https://i.imgur.com/vh1MFFN.png)
> The ltxprimer / Indian TeX Group

TeX排版语言的相当棒的入门参考。虽然这本小册子比较老，但是由于它主要关注TeX的核心方面，所以依然有很大的参考价值。

![](https://s-media-cache-ak0.pinimg.com/originals/ce/fa/f4/cefaf47039ce09db0cb5c199bb5ddf23.jpg)
> opengl-tutorials.org

OpenGL边学边做，讲解详细，代码质量也不错。

> The Linux Command Line / William Shotts

相当棒、相当精简、信息密度极大的介绍GNU/Linux（debian），bash programming和日常工具（grep, sed等）的手册。是以后/正在使用Linux的同学绝佳的自学教程 / 参考资料。更重要的是， 这本书是开源免费的！

> http://www.learncpp.com/

相当赞的在线C++知识参考网站，有详细的例子，体系完备技术新颖，适合自学C++或者查漏补缺。

![enter image description here](https://www.packtpub.com/sites/default/files/B03687_Unreal%20Engine%20Game%20Development%20Cookbook_.jpg)
> Unreal Engine Game Development Cookbook, John P. Doran

UE4的入门读物，从实例入手讲解如何进行简单游戏的开发。

一些不错的书单推荐：

https://zhuanlan.zhihu.com/p/24207171
http://www.cc.gatech.edu/~turk/math_gr.html
http://peterwonka.net/Documentation/BooksToRead.htm



