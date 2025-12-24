# JINGYU Christmas Tree (V9.1 Ultra Stable)

- Three.js r128 + Bloom 后期 + ACES tone mapping
- MediaPipe Hands（检测到手自动点亮）
- 即使摄像头不可用：点击页面也可切换点亮/熄灭（方便演示/调试）
- 页面内置红色错误浮层：若出现黑屏/空白，会显示具体报错，便于定位

## GitHub Pages
建议使用：
- Settings -> Pages -> Source: Deploy from a branch
- Branch: main (或 master) / Folder: /(root)

## 常见问题
### 黑屏/空白
- Bloom/EffectComposer 需要 `Pass.js`，缺失会导致直接报错。
- 本版本已包含 Pass.js，且会在左上角显示错误浮层。

### 摄像头不可用
- 需要 HTTPS 或 localhost
- 浏览器需要允许摄像头权限
