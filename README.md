# AndDream 3D — Immersive Brand Experience / 品牌沉浸式 3D 体验

An interactive 3D webpage for the AndDream brand. Dark space, liquid mercury spheres, particle systems, and an orbiting text ring — scroll to navigate through the scene.

AndDream 品牌的交互式 3D 网页。深色空间、液态水银球体、粒子系统与环绕文字带，滚动控制镜头在场景中穿行。

---

## Preview / 预览

- **Central blob**: Giant frosted liquid-metal sphere with dramatic surface deformation
- **Text ring**: Fluorescent serif lettering — **ANDREAM** · The Dream That Continues — orbiting the equator
- **Outer blobs**: 340 small mercury spheres scattered in surrounding space
- **Droplet interaction**: 500 particles splashing from and merging back into the central blob
- **Background particles**: 11,000 particles in warm and cool layers
- **Lighting**: 7-color ring lighting (red, orange, gold, green, blue, violet, pink) for kaleidoscopic reflections
- **Navigation**: Scroll-driven infinite camera orbit with auto-drift

---

- **中央球体**：巨型磨砂液态金属球，伴随强烈的流动形变动画
- **文字环**：荧光衬线字环绕赤道 — **ANDREAM** · The Dream That Continues
- **外围球体**：340 颗小型水银球体散布在周围空间
- **液滴互动**：500 颗粒子与中心球体互动（飞溅、轨道运行、重力回落）
- **背景粒子**：11,000 颗冷暖双层粒子
- **灯光**：7 色环形布光（红、橙、金、绿、蓝、紫、粉），各角度呈现不同彩色光泽
- **导航**：滚动驱动镜头环绕，自动缓慢漂移，无限循环

---

## How to Open / 打开方式

Open `index.html` directly in a browser. No build tools or server required.

直接用浏览器打开 `index.html` 即可，无需任何构建工具或服务器。

> Internet connection required for Google Fonts and Three.js CDN. Chrome or Edge recommended.
> 需要联网加载 Google Fonts 和 Three.js CDN。推荐使用 Chrome 或 Edge。

## Controls / 操作

| Input / 操作 | Effect / 效果 |
|------|------|
| **Scroll / 滚动鼠标触控板** | Orbit camera through 3D space / 镜头在 3D 空间中环绕 |
| **Touch swipe / 触摸滑动**（mobile / 移动端） | Same as scroll / 同上 |
| **Idle / 不操作** | Auto-drift / 镜头自动缓慢漂移 |

## Files / 文件说明

| File / 文件 | Purpose / 作用 |
|------|------|
| `index.html` | Main file with all CSS & JS inline / 主文件，包含全部 CSS / JS |
| `index-3D2.0.html` | V2.0 backup / V2.0 版本备份 |
| `index-original.html` | Original static typography version / 最初静态排版版 |
| `AndDream3Doriginal.html` | First 3D version reference / 3D 初版参考 |

## Tech Stack / 技术栈

- **Three.js** v0.160 (CDN)
- Fonts / 字体：Playfair Display / Crimson Pro / Noto Serif SC (Google Fonts)
- WebGL 2.0, zero dependencies, single-file deployment / 零依赖，单文件部署

## License / 许可证

MIT License — 自由使用、修改、分发。
