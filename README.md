# 动态裂纹分叉相场算例

本项目复现了动态裂纹分叉的相场模型算例，基于相场正则化内聚区模型（Phase-Field Regularized Cohesive Zone Model, PF-CZM）。

## 项目描述

本代码库包含用于ABAQUS的用户单元子程序（UEL），实现了动态断裂分析的相场模型。该模型能够模拟动态加载条件下裂纹的扩展、分叉等复杂断裂行为。

代码实现了相场正则化内聚区模型，采用BFGS准牛顿求解器，支持动态断裂分析和多种软化本构关系。

## 裂纹分叉视频演示

![动态裂纹分叉过程](branching.avi)

*点击上方链接查看裂纹分叉的动态过程*

## 参考文献

本项目复现了以下研究工作：

**[1] Nguyen V P, Wu J Y. Modeling dynamic fracture of solids with a phase-field regularized cohesive zone model[J]. Computer Methods in Applied Mechanics and Engineering, 2018, 340: 1000-1022.**
# dynamic_phase_filed
