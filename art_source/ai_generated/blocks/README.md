# 顺风方块：绿色方块视觉母版

8 张独立形状图片，加 1 张已认可的原始视觉母版。形状与 ID 根据用户提供的工程清单制作；云端没有 Cocos 源文件，未独立复核。

| 文件 | 尺寸 | 格式 |
| --- | --- | --- |
| block_green_bar2h.png | 1774 × 887 | PNG / RGBA |
| block_green_bar2v.png | 887 × 1774 | PNG / RGBA |
| block_green_bar3h.png | 2172 × 724 | PNG / RGBA |
| block_green_bar3v.png | 724 × 2172 | PNG / RGBA |
| block_green_lleft.png | 1312 × 1199 | PNG / RGBA |
| block_green_lright.png | 1312 × 1199 | PNG / RGBA |
| block_green_single.png | 1312 × 1199 | PNG / RGBA |
| block_green_square2.png | 1254 × 1254 | PNG / RGBA |
| reference_approved_green_L.png | 1312 × 1199 | PNG / RGBA |

## 几何和验收

- lleft 为上左、下左、下右（右上缺角）；lright 为上右、下左、下右（左上缺角）。原始参考图缺角在右下，只作为材质参考，不是这两种游戏形状。
- 视觉检查：各主体无箭头与明显内部分割线，均有透明区域；两种 L 的缺角朝向按示意制作。透明边缘仍有少量黄绿色杂边，部分阴影和边缘厚度不同，需在深浅底色和相邻格场景检查。
- 文件画布、留白和可见主体尺度各不相同，单格像素尺寸、圆角半径、阴影范围与透明边缘未统一，不能直接保证贴合统一网格。请先依真实 cells 制作精确蒙版、对齐锚点和尺度，再进行 Cocos 3.8.8 场景验证。
- 没有执行 Cocos 工程集成、像素级占格或真机测试；这些是待验收视觉母版，并非已验证的正式工程素材。
- 箭头由游戏动态叠加；不要按旧资源的 180° 补偿假定新图方向。请以当前游戏代码和实际场景测试为准。
