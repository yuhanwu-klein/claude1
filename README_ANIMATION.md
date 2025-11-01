# 角色跑步动画 / Character Running Animation

这个项目为Art Deco风格的角色添加了跑步动画效果。

## 文件说明

- `0a1a318d43e044b0d29fdbce0db38191.jpg` - 原始角色图片
- `character_running_animation.html` - 跑步动画演示页面

## 如何使用

1. 在浏览器中打开 `character_running_animation.html` 文件
2. 你将看到角色在屏幕中央以跑步动画展示
3. 使用左上角的控制面板可以：
   - 调整动画速度（0.2x - 2.0x）
   - 暂停/继续动画

## 动画特性

- **弹跳效果**：模拟跑步时的上下起伏
- **身体倾斜**：模拟跑步时的身体动态
- **背景滚动**：营造移动感
- **速度指示器**：根据速度显示不同的运动状态（WALK/JOG/RUN/SPRINT）
- **可调节速度**：从慢走到快跑，完全可控

## 技术实现

使用纯HTML + CSS3动画实现，无需任何JavaScript框架，包括：
- CSS3 关键帧动画 (keyframes)
- CSS3 变换 (transform)
- 动画播放状态控制

## 浏览器兼容性

支持所有现代浏览器（Chrome, Firefox, Safari, Edge）。
