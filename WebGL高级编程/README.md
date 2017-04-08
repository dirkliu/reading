# WebGL高级编程知识点汇总
*书名：*WebGL高级编程
*著：*[美] Andreas Anyuru

## 1.WebGL图形流水线的总体结构

```flow
st=>start: Web Applications HTML + CSS + Javascript + Shader Source Code + 3D Modeling Data
webGLJavascriptApi=>operation: WebGL Javascript Api
vertex=>operation:顶点着色器
assembly=>图元装配
rasterization=>光栅化
fragmentShader=>片段着色器
cuttingTest=>裁剪测试
multipleSampling=>多重采样,片段运算
templateTest=>模板测试
deepCache=>深度缓存测试
merge=>融合
shake=>抖动
e=>end: 绘制缓存
st->webGLJavascriptApi->vertex->assembly->rasterization->fragmentShader->cuttingTest->multipleSampling->templateTest->deepCache->merge->shake->e
```

## 2.需掌握的线性代数知识

 * 坐标系，点，标量与矢量
    三维空间的点和矢量可以用三个坐标分量指定
 * 矢量的点积与叉积
 * 齐次坐标
   为了区分3D空间的点和矢量，额外引入一个坐标（w）。w=0，表示矢量；w≠0,表示点
 * 矩阵
   矩阵的相加与相减，矩阵相乘，单位矩阵，逆矩阵，转置矩阵
 * 仿射变换
   以定点或矢量为运算对象，用某种方法对它进行转换。
   平移， 旋转， 缩放， 剪切

## 3 知识结构整理
### 3.1 webGL库与框架
### 3.2 纹理贴图
 * 丢失上下文
 * 2D纹理与3D纹理
 * 纹理处理的流程： 载入->定坐标->着色器处理->过滤
### 3.3 处理动画与用户输入
### 3.4 使用光照
### 3.5 性能优化

## 4 总结


