poseWrangler
============

![alt tag](epic_pose_wrangler/docs/site/html/_images/v2.png)

概述
---------------
PoseWrangler是一个用于与Epic的MayaUERBFPlugin进行接口交互的工具。该插件由Epic Games分发，并通过Quixel Bridge安装。这是与Maya插件（v6.9.2或更高版本）一起通过Quixel Bridge分发的相同版本。
 - 支持使用UERBFSolverNode创建的场景
 - 多驱动程序支持
 - 初始混合形状支持（WIP）
 - 支持Maya 2018-2022
 - 支持自定义镜像映射，允许使用与默认UE5约定不同的命名约定的绑定
 - 可以通过Python和MayaPy完全自动化
 - 序列化/反序列化为字典或JSON文件
 - 支持自定义扩展和上下文菜单操作

贡献者
---------------
 - Chris Theodosius
 - Chris Evans
 - Judd Simantov
 - David Corral
 - Borna Berc

打开工具
---------------
要加载该工具，可以这样调用它：

```
from epic_pose_wrangler import main
pose_wrangler = main.PoseWrangler()
```
