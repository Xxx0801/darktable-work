# 风光后期流程

> 本文件建立五类风光场景的后期流程：自然风光、新疆/西北风光、城市建筑、日落照片、夜景照片。
> 风光后期五大重点：天空恢复、动态范围、色彩氛围、空间感、细节增强。

---

## 1. 自然风光

**重点**：天空层次、动态范围、色彩氛围、空间感、细节增强

**darktable 操作顺序**
1. 裁剪与旋转（Crop and Rotate）— 矫正地平线、构图
2. 镜头校正（Lens Correction）— 去畸变/暗角/紫边
3. 曝光（Exposure）— 整体亮度
4. 色调均衡器（Tone Equalizer）— 压低天空、恢复暗部，平衡动态范围
5. 白平衡（White Balance）— 按时间/氛围定冷暖
6. RGB 色彩平衡（Color Balance RGB）— 塑造氛围、冷暖对比
7. 局部对比度（Local Contrast）— 增强山体/岩石/云层层次
8. 扩散或锐化（Diffuse and Sharpen）— 增强纹理
9. （如需要）降噪（Denoise）— 天空/阴影去噪

**调整重点**
- 天空不过曝、暗部有细节。
- 冷暖对比自然，符合时间感。

**避免问题**
- 天空压暗过度出现断层/光晕。
- 局部对比度过高导致噪点、画面脏。

---

## 2. 新疆/西北风光

**特点**：大光比、戈壁/沙漠/雪山、色彩浓郁、通透的蓝与暖调并存。

**darktable 操作顺序**
1. 裁剪与旋转（Crop and Rotate）— 大场景构图、地平线
2. 镜头校正（Lens Correction）— 广角畸变
3. 曝光（Exposure）— 整体亮度
4. 色调均衡器（Tone Equalizer）— 大光比恢复（天空/阴影）
5. 白平衡（White Balance）— 强化通透感
6. RGB 色彩平衡（Color Balance RGB）— 蓝天通透、沙/山暖调
7. 局部对比度（Local Contrast）— 增强沙丘/山体质感
8. 扩散或锐化（Diffuse and Sharpen）— 细节

**调整重点**
- 动态范围优先：天空通透、暗部不死黑。
- 色彩通透不浑浊，蓝天干净。

**避免问题**
- 饱和度拉太高导致蓝天发假、画面油腻。
- 大光比下强行提阴影产生噪点。

---

## 3. 城市建筑

**重点**：透视垂直、质感、冷暖对比。

**darktable 操作顺序**
1. 透视校正（Perspective Correction）— 拉直建筑垂直线
2. 镜头校正（Lens Correction）— 去畸变
3. 裁剪与旋转（Crop and Rotate）— 构图（透视校正后）
4. 曝光（Exposure）— 整体亮度
5. 色调均衡器（Tone Equalizer）— 压天空、提建筑
6. RGB 色彩平衡（Color Balance RGB）— 冷暖对比、城市氛围
7. 局部对比度（Local Contrast）— 增强建筑/玻璃质感
8. 扩散或锐化（Diffuse and Sharpen）— 细节

**调整重点**
- 垂直线拉直，建筑不歪斜。
- 玻璃/金属质感与冷暖对比。

**避免问题**
- 透视校正过度导致不自然、裁切过多。
- 局部对比度过强让玻璃反光生硬。

---

## 4. 日落照片

**重点**：天空恢复、暖调氛围、层次。

**darktable 操作顺序**
1. 裁剪与旋转（Crop and Rotate）— 构图
2. 曝光（Exposure）— 整体亮度（略压以保留天空）
3. 色调均衡器（Tone Equalizer）— 恢复天空高光、提暗部
4. 白平衡（White Balance）— 偏暖，强化日落氛围
5. RGB 色彩平衡（Color Balance RGB）— 高光暖、暗部可略冷
6. 局部对比度（Local Contrast）— 云层层次
7. 扩散或锐化（Diffuse and Sharpen）— 细节

**调整重点**
- 天空层次丰富，高光不溢出。
- 暖调氛围浓而不脏。

**避免问题**
- 为保天空把地面压太暗失去细节。
- 白平衡过暖导致画面发黄发闷。

---

## 5. 夜景照片

**重点**：噪点控制、暗部层次、灯光色彩。

**darktable 操作顺序**
1. 裁剪与旋转（Crop and Rotate）— 构图
2. 镜头校正（Lens Correction）— 灯光色差/紫边
3. 曝光（Exposure）— 整体亮度（夜景通常需提亮）
4. 降噪（Denoise）— 先降噪（高 ISO 夜景重点）
5. 色调均衡器（Tone Equalizer）— 提暗部、控高光灯光
6. 白平衡（White Balance）— 修正路灯/霓虹偏色
7. RGB 色彩平衡（Color Balance RGB）— 灯光氛围、冷暖对比
8. 局部对比度（Local Contrast）— 适度
9. 扩散或锐化（Diffuse and Sharpen）— 轻度

**调整重点**
- 降噪与细节的平衡（夜景易噪点）。
- 暗部有层次，灯光不过曝。

**避免问题**
- 过度降噪导致塑料感、细节糊。
- 提亮过度让噪点更明显、暗部发灰。
